# JavaScript Loops

The **JavaScript loops** are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

- There are four types of loops in JavaScript:

1.  for loop
2.  while loop
3.  do-while loop
4.  for-in loop

# 1) JavaScript For loop

The JavaScript **for loop** iterates the elements for the fixed number of times. It should be used if number of iteration is known. The syntax of for loop is given below.

> The Formula of **for loop**

- for (initialization; condition; increment)  
  {  
   code to be executed  
  }

## EXAMPLE

- \<script>  
  for (i=1; i<=5; i++)  
  {  
  document.write(i)  
  }  
  \</script>

**Output:**

1

2

3

4

5

# 2) JavaScript while loop

The JavaScript **while loop** iterates the elements for the infinite number of times. It should be used if number of iteration is not known. The syntax of while loop is given below.

> The Formula of **while loop**

- while (condition)  
  {  
   code to be executed  
  }

## EXAMPLE

- \<script>  
  var i=11;  
  while (i<=15)  
  {  
  document.write(i);  
  i++;  
  }  
  \</script>

**Output:**

11

12

13

14

15

# 3) JavaScript do-while loop

- The JavaScript **do-while loop** iterates the elements for the infinite number of times like while loop. But, code is executed at least once whether condition is true or false. The syntax of do while loop is given below.

> The Formula of **while loop**

- do{  
   code to be executed  
  }while (condition);

## EXAMPLE

<script>  
var i=21;  
do{  
document.write(i + "<br/>");  
i++;  
}while (i<=25);  
</script>

**Output:**

21

22

23

24

25

# 4) JavaScript for in loop

- The JavaScript for in loop is used to iterate the properties of an object. We will discuss about it later.
