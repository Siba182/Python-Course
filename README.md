# Python-Week-1
Work done during the first week of learning Python


1. INTRODUCTION
   
'jupyter notebook'
Command to open and run jupyter from the browser

Using VS Code as my IDE
To run a code on VS Code
-	Create a file
-	Write the code on VS Code
-	Open a new terminal
-	Navigate to the correct directory
-	Type Python with the file name 

Alteratively, using Jupyter
Creating a file, write code and run it from the browser
You can use same file and run it on VS Code


2. GETTING STARTED
   
Variable
-	 case sensitive and traditionally starts with a lower case.
  
Types of variables
Integer – whole numbers (3)
Floats –  decimal numbers (3.5)
Complex numbers- used for mathematical calculation.
Strings -  which are collections of characters (‘Sibabalwe’)
Booleans - which are true or false values
+ used to concatenate strings




Data Structures
-	data structures allow for the storage of a list of values in a single variable.
   
Types of Data Structures
List 
- can contain any data type, including a list within a list. 
- The length of a list can be determined using the length function.

Set 
- similar to a list, except it only contains unique elements and is declared using curly braces.
- The order of elements in a set is not important, unlike in a list

Tuple
- similar to lists, except they cannot be modified once declared
- useful when you need to store large data into memory

Dictionary
- is a collection of key-value pairs, similar to a word and its definition in a book
- is declared using curly braces and accessed using keys



Operators
- instructions that perform operations on variables and values in Python

Arithmetic Operator
- used for mathematical calculaton

Types of Arithmetic 
Addition + 
- add two numbers together

Multiplication *
- multiplies two numbers together
- 
Exponent **
- which raises a number to a specified power
 
Division /
  - returns a float even if the result is a whole number
Modulus %
- provides the remainder after division
  
Concantenating +
- works only on strings to combine them
  
Multiplication String *
- can used to repeat a string a certain number of times. Works on 
  strings and numbers

Comparison Operator ( ==, >, >=, <, <=)
- compares two values and produces a boolean

Logical Operator
- "and" - returns true if both operands are true
- "or" - returns true if at least one operand is true
- "not" - negates the Boolean value it operates on

Membership Operator
- "in" and "not in" - used to check whether a value is present in a sequence or note



Control Flow
- if statement - it executes a block of code only if a condition is met 
- for loop - to iterate over a list 
- while loop - keeps looping until a certain condition is false


Functions 
- is like a machine that takes inputs and produces outputs

- how to define a function
def functionName (argument) 
 return value

 - other function does not have any return value but uses print to print to the console

3. BASIC STARTER TYPES

INTS and FLOATS
- Python automatically returns a float to accommodate non-whole numbers
- Adding a float to an int, multiplication or exponents will return a float

Casting
- conversion from one type to another
- doesnt round numbers, it just removes the decimal part eg 8.9 will be 8
- to round a float to an int you use the round function eg round(14/3) will be 5
- you can also round to the nearest decimal when calculating floats. eg. round(1.2 - 1.0, 2) will be 0.2


Alternative Number Types
Integer 
- passing a number as a strng it, the int class converts it to an integer

Decimal 
- better than the float if you will be dealing with money
- you will need to import the decimal class and the getcontect function
- the getcontext function hold a global setting for using the decimal class

Booleans
- integers are casted(converted) to booleans
- anything except 0 is true
- Boolean true is true
- empty strings is false
- 'false' is true as it is a string that is not empty
- Data structures can also be casted as booleans
- an empty list or dictionary is false

Strings 
Slicing
- refers to taking a portion of a string and returning it using its index position

Formating
- formatting is string concatenating using the +
- using the f-string ( f'{expression}')

Multi-line String
- use tripple qoutes to create multiple lines '''
- escape using backslashes for each ending qoutes

Byte
- sequence of data
- a byte object that is 4 bytes long is byte(4)
- Each bytes has 8 bits
- byte objects start with a b


4. BASIC DATA STRUCTURE
