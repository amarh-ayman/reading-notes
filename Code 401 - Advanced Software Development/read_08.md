# List Comprehensions in Python

- a quick way to create lists
- > It consists of brackets containing an expression followed by a for clause, then
  > zero or more for or if clauses. The expressions can be anything, meaning you can
  > put in all kinds of objects in lists.

- **Example**
- _OPTION |_

  > new_list = []
  > for i in old_list:

      if filter(i):
          new_list.append(expressions(i))

- _OPTION ||_
  > new_list = [expression(i) for i in old_list if filter(i)]

## Basic Syntax

square brackets []

# More Examples

> You can either use loops:

    squares = []

    for x in range(10):
        squares.append(x**2)

    print squares
    [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]

    # Or you can use list comprehensions to get the same result:
    squares = [x**2 for x in range(10)]

    print squares
    [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
