# MITCourses
## Introduction to Computer Science and Programming in Python - Dr. Ana Bell

### Pre Requisite:
* Programming Language and Scripting Language
* Program: A sequence of instructions written so that a computer can perform certain task.
* Script: You can write code to control another software application. They have short development cycle and can be created and deployed rapidly.
* All Scripting Language are programming language. Scripting language do not require compilation and are interpreted instead.
* Python:-
     * General Purpose Language
     * Interpreted
     * High Level
     * Indentation is a requirement
     * Strength is huge collection of Standard Library
     * Lets you work quickly and integrate system more efficiently
     * Performs automatic memory management
     * Supports Operator Overloading
     * Provides both single and multiple inheritance
     * Platform Independent
     * Supports Multithreading
     * Supports Structured and OOP programming paradigm
     * Provides high level dynamic data types and supports dynamic checking: 
            1. It stores the value at some memory location 
            2. Binds the variable name to that memory container
            3. Makes content of container accessible through the Variable name
     * Can be easily integrated with C, C++, Java
     
     
### Lecture 1:



### Lecture 2:



### Lecture 3:



### Lecture 4:



### Lecture 5:


### Lecture 6:


### Lecture 7:


### Lecture 8:


### Lecture 9:


### Lecture 10:



### Lecture 11:


### Lecture 12:

### Memory Allocation and Memory Management in Python
Code:
x=10 <br />
print(type(x)) <br />
This will give output as: <class:int> because everything is object in python so x will point to the container which has value 10 present in it <br />
y=x <br />
This will create another reference variable 'y' which will contain reference to the same object in this case 10 <br />
To verify let us compare their memory location using 'id function' <br />
if(id(x)==id(y)): print("x and y refer to the same object") <br />
This will give an output as: "x and y refer to the same object" which means both x and y are refering to the same object <br />
x=x+1 <br />
Now this makes x=11 and x starts refering to a new object which is a container that contains 11 <br />
if(id(x)!=id(y)): print("they refer to different objects") <br />
This shows that x=11 and y=10 refer two different objects <br />
z=10 <br />
Now let us create a third variable z and let us compare its id with y <br />
if(id(z)==id(y)): print("z and y refer to the same object") <br />
else: print("z and y refer to different objects") <br />
The output is that: "z and y refer to the same object" which is surprising and the reason is python optimizes memory utilisation by allocating the same object reference to a new variable if the object already exists with the same value <br />
z="riya" <br />
print(type(z)) <br />
The output is: <class 'str'> <br />
Therefore Python is dynamically typed language <br />


