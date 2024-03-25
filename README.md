<details>
<summary> Week 1 </summary>
<br>
 


# Python-Week-1
Work done during the first week of learning Python


**1. INTRODUCTION**
   
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


**2. GETTING STARTED**
   
**Variable**
-	 case sensitive and traditionally starts with a lower case.

  
**Types of variables**
- Integer – whole numbers (3)
- Floats –  decimal numbers (3.5)
- Complex numbers- used for mathematical calculation.
- Strings -  which are collections of characters (‘Sibabalwe’)
- Booleans - which are true or false values
- used to concatenate strings +




**Data Structures**
-	data structures allow for the storage of a list of values in a single variable.
   
**Types of Data Structures**

**List** 
- can contain any data type, including a list within a list. 
- The length of a list can be determined using the length function.

**Set** 
- similar to a list, except it only contains unique elements and is declared using curly braces.
- The order of elements in a set is not important, unlike in a list

**Tuple**
- similar to lists, except they cannot be modified once declared
- useful when you need to store large data into memory

**Dictionary**
- is a collection of key-value pairs, similar to a word and its definition in a book
- is declared using curly braces and accessed using keys



**Operators**
- instructions that perform operations on variables and values in Python

**Arithmetic Operator**
- used for mathematical calculaton

**Types of Arithmetic**

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

**Comparison Operator** ( ==, >, >=, <, <=)
- compares two values and produces a boolean

**Logical Operator**
- "and" - returns true if both operands are true
- "or" - returns true if at least one operand is true
- "not" - negates the Boolean value it operates on

**Membership Operator**
- "in" and "not in" - used to check whether a value is present in a sequence or note



**Control Flow**
- if statement - it executes a block of code only if a condition is met 
- for loop - to iterate over a list 
- while loop - keeps looping until a certain condition is false


**Functions** 
- is like a machine that takes inputs and produces outputs

- how to define a function
def functionName (argument) 
 return value

 - other function does not have any return value but uses print to print to the console

**3. BASIC STARTER TYPES**

**INTS and FLOATS**
- Python automatically returns a float to accommodate non-whole numbers
- Adding a float to an int, multiplication or exponents will return a float

**Casting**
- conversion from one type to another
- doesnt round numbers, it just removes the decimal part eg 8.9 will be 8
- to round a float to an int you use the round function eg round(14/3) will be 5
- you can also round to the nearest decimal when calculating floats. eg. round(1.2 - 1.0, 2) will be 0.2


**Alternative Number Types**

**Integer** 
- passing a number as a strng it, the int class converts it to an integer

**Decimal** 
- better than the float if you will be dealing with money
- you will need to import the decimal class and the getcontect function
- the getcontext function hold a global setting for using the decimal class

**Booleans**
- integers are casted(converted) to booleans
- anything except 0 is true
- Boolean true is true
- empty strings is false
- 'false' is true as it is a string that is not empty
- Data structures can also be casted as booleans
- an empty list or dictionary is false

**Strings**

**Slicing**
- refers to taking a portion of a string and returning it using its index position

**Formating**
- formatting is string concatenating using the +
- using the f-string ( f'{expression}')

**Multi-line String**
- use tripple qoutes to create multiple lines '''
- escape using backslashes for each ending qoutes

**Byte**
- sequence of data
- a byte object that is 4 bytes long is byte(4)
- Each bytes has 8 bits
- byte objects start with a b


**4. BASIC DATA STRUCTURE**

**Lists**
**Lists Sclicing**
- slicing can be used to extract a range of values from a list or string
- range function can be used to produce longer lists
- negative values can be used to step back backward through the list
- slicng also has a step functionality, index position, the last number and the amount of 
   times you can step through a list [0:6:2]


**Modifying List**

- append() - to add an item to the end of a list eg 1,2,3,4 mylist.append(5)
- insert() - to insert an item at a specific position in the list eg insert value 10 at 
   position 3, myList.insert(3,10)
- remove() - removes an item from the list base on its value and not index. eg 
   myList.remove(5) will remove the value 5 and if 5 is not on the list, program will throw 
   an error
- pop() - removes the last item in the list
          in the while loop, it can remove the entire loop if the condition set is true 

**Sets**
- defined using curly braces
- also defined by passing iterable object in the constructor of the set class
- sets only contains unique values so it will remove any duplicates in the list
- does not contain an ordered list
- cannot access elements in a set using index or slicing
- can add on the set using add()
- can remove on the set using discard()

**Tuple**
- similar to lists but declared using round brackets
- cannot be modified
- can get an element using index
- take up less memory - good for when you have large amount of data to store

**Dictionary**
- a collection of key values pairs ordered and changeable
- no duplicates
- defined using curly braces
- to get a specific dictionary you call the dictionary with a key inside square braces
- to add a new key you can call the dictionary with the key in square braces and assigning 
  it a value
- to a update an existing value, call the dictionary with the existing key inside square 
  braces with a new value
- you can access the keys and values individually using .keys() and values() method 
  respectively

**List Cmprehension**
- has to do with the comprehensive listing of things
- similar syntax to that of a loop
- create a loop in one line while also returning a copy of the list being iterated over

- split() function allows you to split a sting based on a character or string.
- cleanWord() fuction allows you to replace characters in a string using the below functions
- replace() replaces a certain character
- lower() makes all first characters of a word a lower case


**Dictionaries and Comprehensions**
-


**5. Basic Control Flow**
if and else-

While loop
- to exit the loop and run the next code, you use the break statement
- continue -if you want to skip certain lines in the loop 

</details>

<details>
<summary> Week 2 </summary>
<br>


 **Functions**

- is like a machine that takes inputs and produces outputs

- how to define a function def functionName (argument) return value

- other function does not have any return value but uses print to print to the console

You can override on a function
![image](https://github.com/Siba182/Python-Course/assets/60964130/1a19f877-8642-4cdb-a044-b570788bd2c2)


*args
- they must come after the positional arguments
- The order of the first two arguments is important and cannot be changed
- after these mandatory arguments, the keyword arguments can be in any order
- only for positional argument


**kwargs (keyword arguments)
- use kwargs to handle keyword arguments
- stored as a dictionary as they have keys and values
- can be passsed in any order
  

**Variables and Scope**

**Locals**
- variable names that are only accessible locally within the function
- can be defined by any name within the function definition, and it will be available anywhere within that function
-  trying to reference a variable outside its scope will result in an error. 


**Globals**
- outside the function
- looks up the variable's data, it checks the local scope first and then the global scope.
- redefine a message in function one's local scope and print both the local and global values of the message


**Functions as Variables**
- variables and functions both have names and data associated with them
- for functions, this data includes information about required parameters and the lines of instruction to be executed
-  a function is represented as an object.



Viewing Function Data With  __code__

![image](https://github.com/Siba182/Python-Course/assets/60964130/3dcb7117-6402-4507-bc1f-be4b53cdf604)


**Static and Instance Methods**
![image](https://github.com/Siba182/Python-Course/assets/60964130/d3045471-37dc-4bda-afe1-d67c6db9975b)


- the cleanText() is a static method because it does not belong to any class instance
- addText() is an instance method that belongs to a an instance of the a class
- Static variables like replace puncs can also be added to control which punctuations get 
  replaced
- Use either the class name or the class instance to refer to static variables, but cannot be 
  done with instance methods


**Decorator**
- a special annotation or description for a function definition.


**Inheritance**
- it is possible for one class to inherit all the methods and attributes of another class
- The original class is referred to as the parent class, while the new class that extends it is 
   known as the child class
- This inheritance process happens automatically when the child class is created.
- you can overwrite a parent class if you wish to add or change a method
- you can also add new methods on child classes
- useful for when an existing class is used but needs a few changes or additions 



**Handling Errors and Exceptions**



















</details>
