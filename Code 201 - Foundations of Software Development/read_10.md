# Error Handling & Debugging

Error handling, as the name states, is a strategy that handles the errors or exceptions which occur at runtime. Javascript is a loosely coupled language, so it doesn’t raise many errors at the compile/interpretation level, and you will see many mistakes at runtime only. Few of the common examples which can lead to a runtime error are:

When you try to access a variable or property, which is undefined.
When you try to access an undefined method
In all the above cases, an error occurs, which results in terminating the program abruptly or stops the execution without completing. It might cause a problem in many cases like someone opens a database connection and the program fails/crashes without gracefully closing the database connection, which may lead to a situation of exhausting the number of allowed connection to the database instance and may lead to a situation where the database itself becomes inaccessible.

- If you understand execution contexts (which have two 
stages) and stacks, you are more likely to find the error 
in your code. 
- Debugging is the process of finding errors. It involves a 
process of deduction. 
- The console helps narrow down the area in which the 
error is located, so you can try to find the exact error. 
- JavaScript has 7 different types of errors. Each creates 
its own error object, which can tell you its line number 
and gives a description of the error. 
- If you know that you may get an error, you can handle 
it gracefully using the try, catch, finally statements. 
- Use them to give your users helpful feedback. 