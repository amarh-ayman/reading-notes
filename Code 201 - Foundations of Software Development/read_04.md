# LINKS

Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.<br><br>

### You will commonly come across the following types of links:

- Links from one website to another
- Links from one page to another on the same website
- Links from one part of a web page to another part of the same page
- Links that open in a new browser window
- Links that start up your email program and address a new email to someone

<br><br>

### The \<a> tag indicates where the hyperlink starts and the \</a> tag indicates where it ends. Whatever text gets added inside these tags, will work as a hyperlink. Add the URL for the link in the \<a href=” ”>. Just keep in mind that you should use the \<a>…\</a> tags inside \<body>…\</body> tags.

## EXAMPLE

\<a href="/about/about_team.htm">team\</a>
<br><br>

- Links are created using the \<a> element.
- The \<a> element uses the href attribute to indicate the page you are linking to.
- If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
- You can create links to open email programs with an email address in the "to" field.
- You can use the id attribute to target elements within a page that can be linked to.
  <br><br>

# LAYOUT

- \<div> elements are often used as containing elements to group together sections of a page.
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.
  <br><br>
  ![img](https://th.bing.com/th/id/R9369be43ae1eaac13467a6b6cdaf7233?rik=1lgsbL%2fNCtX4DA&riu=http%3a%2f%2fm5designstudio.com%2fwp-content%2fuploads%2f2013%2f02%2fcss-layout-using-floats.png&ehk=18wVKcDIjjsmSTNLuOUNjmVd3ERrYipGxmjXa1ocSoA%3d&risl=&pid=ImgRaw)

There are **tons** of different layout designs to choose from. However, the structure above, is one of the most common.

<br><br>

- Header
  - A header is usually located at the top of the website
- Navigation Bar
  - A navigation bar contains a list of links to help visitors navigating through your website
- Content
  - The layout in this section, often depends on the target users.
- Footer
  - The footer is placed at the bottom of your page. It often contains information like copyright and contact info

<br><br>

# WHAT IS A FUNCTION?

**Functions** let you group a series of statements together to perform a
specific task. If different parts of a script **repeat the same task**, you can
**reuse** the function (rather than repeating the same set of statements).

for making functions you need to make declarations first by give it name and open braces then write any statements needed
as

- function sayHello( ){
  document.write('Hello!'); }


    # Calling Functions

- is a process used if you need the code you wrote or any function in the system

- you can call it by :
  - sayHello( )
    - write the name of the function

> so for make the process more easier on you at CALLING Function just make the name of it simple .

# OBJECT'S

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

# 6 Reasons for Pair Programming

Iterative loops. Code reviews. Fast feedback. Error checking and linting. These are software engineering practices that have proven to dramatically improve the quality of code developers produce.

pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding,

The Navigator uses their words to guide the Driver but does not provide any direct input to the computer.

Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.
<br>

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness
