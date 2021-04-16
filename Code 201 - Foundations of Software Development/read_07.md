# TAbles

A table is nothing but a means of arranging data in rows and columns. This concept has been present in our society for a long time and has been adopted by HTML in its early stages, as a way to convey information that might otherwise not be obvious or readily understood.

In HTML documents a table can be considered, in a simple way, as a group of rows containing each a group of cells. This is conceptually different to a group of columns containing a group of cells, and this difference will have some impact in the composition and behavior of the table.

Like many other structures in HTML, tables are constructed using elements. In particular, a basic table can be declared using three elements, namely, table (the main container), tr (representing the rows, containers for cells) and td (representing plain cells). Let's make it clear with an example:

\<table class="default">

  \<tr>

    <td>Cell 1</td>

    <td>Cell 2</td>

    <td>Cell 3</td>

  \</tr>

  \<tr>

    <td>Cell 4</td>

    <td>Cell 5</td>

    <td>Cell 6</td>

  \</tr>

\</table>

Cell 1|Cell 2|	Cell 3
------|------|-----
Cell 4|	Cell 5 |Cell 6

<br><br>
Note that this table has been formatted usign CSS to improove comprehension and readability. Authors shouldn't expect these results in tables with no presentational properties assigned.

You can clearly see, in the previous example, the concept of rows containing cells we talked about before. Here it becomes evident how cells, that have been numbered according to their position in the code, follow a sequence in the representation that goes from left to right, one row at a time. This will have further implications, specially when it comes to cell spanning and grouping.

<br><br>
# Functions, Methods, and Objects

- Functions allow you to group a set of related statements together that represent a single task.
- Functions can take parameters (information required to do their job) and may return a value.
- An object is a series of variables and functions that represent something from the world around you.
- In an object, variables are known as properties of the object; functions are known as methods of the object.
- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
- Arrays and objects can be used to create complex data sets (and both can contain the other).
### OBJECT'S

In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.

A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:

### objectName.propertyName
<br><br>

Like all JavaScript variables, both the object name (which could be a normal variable) and property name are case sensitive. You can define a property by assigning it a value. For example, let's create an object named myCar and give it properties named make, model, and year as follows:

var myCar = new Object();<br>
myCar.make = 'Ford';<br>
myCar.model = 'Mustang';<br>
myCar.year = 1969;<br>
<br>

> visit this website 
 [READ 05](https://amarh-ayman.github.io/code-201/code_201/read_06)