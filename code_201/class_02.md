# TEXT

When creating a web page, you add tags(known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

Markup two kind :
- Structure 
    - describe both headings and paragraphs

- Semantic 
    -  provides extra information; such as where emphasis is placed in a sentence


## STRUCTURE

structre | tag's 
 ----|-----
 Heading | \<h1> <br><br> \<h2>  
 Paragraph | \<p>
 Bold | \<b>
 Itelic | \<i>
 Superscript | \<sup>
 Subscript | \<sub>
 White Space | new line or spaces between syntance
 Line Break |\<br />
 Horizontal Rules | \<hr />



 ## SEMANTIC
semantic| tag's
 --|--
Bold(imporatance) | \<strong>
itelic | \<em>
Quotations(longer)|\<blockquote> 
Quotations(shorter)|\<q> 
Abbreviations| \<abbr>
Citation | \<cite>
Definitions|\<dfn>
Author Detailes |\<address>




- #### HTML elements are used to describe the **structure** of the page (e.g. headings, subheadings, paragraphs).

- #### They also provide **semantic** information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).


> For more info [VISIT THIS SITE](https://www.tutorialspoint.com/html/html_basic_tags.htm)


# CSS 

- CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

- Rules are made up of selectors and declarations 

- Different types of selectors allow you to target your rules at different elements.

- Declarations are made up of two parts: 
    - the properties of the element that you want to change
    - and the values of those properties. 

- CSS rules usually appear in a separate document, although they may appear within an HTML page.



Selector | Meaning | Example
---------|---------|---------
Universal Selector |Applies to all elements in the document | * { } <br>Targets all elements on the page
Type Selector|Matches element names | h1, h2, h3 { }  <br> Targets the \<h1>, \<h2> and \<h3> elements <br><br>
Class Selector|Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol | .note { }<br> Targets any element whose class attribute has a value of note <br>p.note {} <br> Targets only \<p> elements whose class attribute has a value of note<br><br>
ID Selector| Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol|#introduction {} <br> Targets the element whose id attribute has a value of introduction <br><br>
Child Selector|Matches an element that is a direct child of another |li>a {} <br> Targets any \<a> elements that are children of an \<li> element (but not other \<a> elements in the page) <br><br>
Descendant Selector| Matches an element that is a descendent of another specified element (not just a direct child of that element) |p a {} <br> Targets any \<a> elements that sit inside a \<p> element, even if there are other elements nested between them <br><br>
Adjacent Sibling Selector|Matches an element that is the next sibling of another| h1+p {} <br>Targets the first \<p> element after any \<h1> element (but not other \<p> elements) <br><br>
General Sibling Selector|Matches an element that is a sibling of another, although it does not have to be the directly preceding element| h1~p {} <br> If you had two \<p> elements that are siblings of an \<h1> element, this rule would apply to both <br><br>




# JavaScript

## WHAT IS A SCRIPT AND HOW DO I CREATE ONE ??

- A script is a series of instructions that the computer can follow in order to achieve a goal.
- Each time the script runs, it might only use a subset of all the instructions.
- Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.
- To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help). 

## EXPRESSIONS

An **expression** evaluates into (results in) a single value.
- there are two types of expressions:
    - EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE 
        - var color = 'beige'; 

    - EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
        - var area = 3 * 2; 


## OPERATORS 

 **operators** allow programmers to create a single value from one or more values. 
- same examples in expression and for more 
     - X = 3 > 5
     - Y =(5 >3) && (2 < 4>)
  
  ## ARITHMETI C OPERATORS

  ![img](https://www.circuitcrush.com/wp-content/uploads/C-Operator-Summary-Table.jpg)





# SWITCH STATEMENT 
![switch img](https://th.bing.com/th/id/Ref5e80a9092b9d0681b7368978349f08?rik=ClCPh1YVVcQnjA&riu=http%3a%2f%2fjava.meritcampus.com%2fcore-java-topics%2fimages%2fJava_Switch_Case.jpg&ehk=h0KULaLr9PTo3swgzQokHZ7WUucGdIPNTmZI6eBevIM%3d&risl=&pid=ImgRaw)

![switch](https://javatutoring.com/wp-content/uploads/2016/12/java-switch-statement-407x330.png)










