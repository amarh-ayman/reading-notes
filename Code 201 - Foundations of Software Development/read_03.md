# LIST'S

<br><br>

## three different types:

- **Ordered lists** are lists where each item in the list is
  numbered.
- **Unordered lists** are lists that begin with a bullet point

- **Definition lists** are made up of a set of terms along with the
  definitions for each of those terms.

| list       | Explain                                                                                                                                                                                              | Exmple                                                                                                                                                       | Output                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Order      | \<ol><br> The ordered list is created with the \<ol> element.<br>\<li><br>Each item in the list                                                                                                      | \<ol><br>\<li>First\</li><br>\<li>Second\</li><br>\<li>Third\</li><br>\</ol>                                                                                 | <ol><br><li>First</li><br><li>Second</li><br><li>Third</li><br></ol>                                                                          |
| Unorder    | \<ul><br> The unrdered list is created with the \<ol> element.<br>\<li><br>Each item in the list                                                                                                     | \<ul><br>\<li>First\</li><br>\<li>Second\</li><br>\<li>Third\</li><br>\</ul>                                                                                 | <ul><br><li>First</li><br><li>Second</li><br><li>Third</li><br></ul>                                                                          |
| Definition | \<dl><br>it's consists of a series of terms and their definitions as \<dt> \<dd> <br>\<dt> <br> This is used to contain the term being defined<br> \<dd><br> This is used to contain the definition. | \<dl><br>\<dt>HTML \</dt> <br>\<dd> HyperText Markup Language \</dd> <br> \</dl>                                                                             | HTML<br> HyperText Markup Language                                                                                                            |
| Nested     | You can put a second list inside an \<li> element to create a sublist or nested list within order or unorder list                                                                                    | \<ol><br>\<li>First<br>\<ul><br>\<li>First\</li><br>\<li>Second\</li><br>\<li>Third\</li><br>\</ul>\</li><br>\<li>Second\</li><br>\<li>Third\</li><br>\</ol> | <ol><br><li>First<br><ul><br><li>First</li><br><li>Second\</li><br><li>Third</li><br></ul></li><br><li>Second</li><br><li>Third</li><br></ol> |

# Boxes

<br><br>
![box](https://th.bing.com/th/id/R179cdd0997596497ec840e8a4acc251d?rik=eJnWQPR%2fEpTgzQ&riu=http%3a%2f%2fimage.slidesharecdn.com%2fcss-boxmodel-130811120108-phpapp02%2f95%2fcss-box-model-2-638.jpg%3fcb%3d1376222562&ehk=V4kWTOVj8tSPkrzKDGwEUoUVJN8%2bGPrbx%2bXVZVrsXSI%3d&risl=&pid=ImgRaw)

<br><br>

- CSS treats each HTML element as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding for each box with CSS.
- It is possible to hide elements using the display and visibility properties.
- Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of boxes containing text and the leading.
- CSS3 has introduced the ability to create image borders and rounded borders.

![pic_box](https://th.bing.com/th/id/R4a365b8c64c766f2d0f742ca769f02ba?rik=VvRJHZeu%2b594MA&riu=http%3a%2f%2fwww.csssolid.com%2fimages%2fCSSBoxModelCore.png&ehk=Ce8oTRd%2fHQsgEbX9Adfav%2fD%2f4BeHzPKz4pyl%2bfkltY0%3d&risl=&pid=ImgRaw)

<br><br>

# ARRAYS

An array is a special type of variable. It doesn't just store one value; it stores a list of values.

You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array).
<br>

### **EXAMPLE**

<br>
var colors;<br><br> colors ['white', 'black', ' custom']; <br>
var el document.getElementByld('col ors'); <br>
el . textContent = col ors[O];

# JavaScript Loops

The **JavaScript loops** are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

### There are four types of loops in JavaScript:

| loop          | Explaination                                                                                                                                                                                                                 | Formula                                                                          | Example                                                                                                      | Output                     |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | -------------------------- |
| for loop      | The JavaScript **for loop** iterates the elements for the fixed number of times. It should be used if number of iteration is known. The syntax of for loop is given below.                                                   | for <br> (initialization; condition; increment)<br> { code to be executed <br> } | \<script><br> for (i=1; i<=5; i++)<br> { document.write(i) <br> }<br> \</script>                             | 1<br>2<br>3<br>4<br>5      |
| while loop    | The JavaScript **while loop** iterates the elements for the infinite number of times. It should be used if number of iteration is not known. The syntax of while loop is given below.                                        | while (condition) {<br> code to be executed<br> }                                | \<script><br> var i=11;<br> while (i<=15) {<br>document.write(i);<br> i++;<br> }<br>\</script>               | 1<br>2<br>3<br>4<br>5      |
| do-while loop | The JavaScript **do-while loop** iterates the elements for the infinite number of times like while loop. But, code is executed at least once whether condition is true or false. The syntax of do while loop is given below. | do{<br> code to be executed<br> }while (condition);                              | \<script> <br> var i=21;<br> do{<br> document.write(i + "\<br>");<br>i++;<br> }while (i<=25);<br> \</script> | 21<br>22<br>23<br>24<br>25 |
