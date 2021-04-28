# Functional programming :

a style of building the structure and elements of computer programs

## function is pure or not?

1. It returns the same result if given the same arguments

1. It does not cause any observable side effects

### Map

The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.

# Filter

we want to filter by an attribute.The filter function expects a true or false value to determine if the element should or should not be included in the result collection

# Reduce

The idea of reduce is to receive a function and a collection, and return a value created by combining the items.

# Refactoring JavaScript

Updating the source code without changing the behavior of the application.

“Complexity is anything that makes software hard to understand or to modify."

> — John Outerhout

## What is functional programming?

**It is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data**

_paradigm is a style of building the structure and elements of computer programs_

## Immutability

Unchanging over time or unable to be changed. Its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## Referential transparency

Basically, if a function consistently yields the same result for the same input, it is referentially transparent.

> **_pure functions + immutable data = referential transparency_**

## Functions as first-class entities

The idea of functions as first-class entities is that functions are also treated as values and used as data.

> Functions as first-class entities can:

> - refer to it from constants and variables
> - pass it as a parameter to other functions
> - return it as result from other functions

_The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior._

## Higher-order functions

- takes one or more functions as arguments

- returns a function as its result
