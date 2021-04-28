# Call stack

is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions

- The JavaScript engine :is a single-threaded interpreter comprising of a heap and a single call stack.

- The browser provides web APIs like the DOM, AJAX, and Timers.

- In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.

- At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

# Types of error messages :

1. Reference errors
   This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

1. Syntax errors
   this occurs when you have something that cannot be parsed in terms of syntax

1. Range errors
   Try to manipulate an object with some kind of length and give it an invalid length

# Debugging

the easiest and maybe the most common way its to simply console.log() the variables you want to check

# Example of StackOver Flow:

function callMyself(){
callMyself();
}
callMyself();

The callMyself() will run until the browser throws a “Maximum call size exceeded”. And that is a stack overflow.

---

At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

Manage function invocation (call): meaning step by step OR function by function (synchronous)

---
