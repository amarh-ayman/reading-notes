# FileIO & Exceptions

## Reading and Writing Files in Python

- a file is a contiguous set of bytes used to store data

- Files are constituent of three parts:

  - Header: metadata
  - Data: file contents
  - End of file (EOF): special character

- File Path: refers to where the file is located, consistes of (Folder Path, File Name, Extension)

## Opening and Closing a File

- file = open(‘dog_breeds.txt’)

- file.close()

> Character –> Meaning ‘r’ –> Open for reading (default) ‘w’ –> Open for writing, truncating (overwriting) the file first ‘rb’ or ‘wb’ –> Open in binary mode (read/write using byte data)

## Python Exceptions: An Introduction

In Python, an error can be a syntax error or an exception.

A Python program terminates as soon as it encounters an error.

## Exceptions versus Syntax Errors

- Syntax Errors: sth is wrong with the syntax(extra bracket, extrat comma)
- Exceptions:

  - > occurs whenever syntactically correct Python code results in an error.

- Raising an Exception

  - > x = 10 if x > 5: raise Exception(‘x should not exceed 5. The value of x was: {}’.format(x))

- Handling Exceptions Through try and except Block

  - > def linux_interaction(): assert (‘linux’ in sys.platform), “Function can only run on Linux systems.” print(‘Doing something.’) try: linux_interaction() except: pass

- The else Clause
  - > try: linux_interaction() except AssertionError as error: print(error) else: print(‘Executing the else clause.’)

> the finally is used with the code that should always run
