
# MIT Courses
## Introduction to Computer Science and Programming in Python - Dr. Ana Bell
### Pre Requisite:

* Programming Language and Scripting Language:- 
     * Program: A sequence of instructions written so that a computer can perform certain task.
     * Script: You can write code to control another software application. They have short development cycle and can be created and deployed rapidly.
     * All Scripting Language are programming language. Scripting language do not require compilation and are interpreted instead.
    <br/>
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
     * Since everything in python is an Object, data types are actually classes and variables are instances (objects) of these classes  
     ![Python-data-structure](https://user-images.githubusercontent.com/62128029/116846250-85879000-ac05-11eb-9fa4-4ba30cbabc3e.jpg)
    <br/>
     
### Lecture 1: What Is Computation?
* Important Course Information
* What is Computation?
* Knowledge are of two types: Declerative (Statement of Fact) and Imperative Knowledge (How To?)
* Basic Machine Architecture
* Alan Turing Computation (You can compute anything using 6 basic primitives.) Modern Programming Language have more convinient set of primitives. Anything computable in one programming language is computable in any other programming language.
* Python Basics: Syntax and Semantics.
* Everything in Python is an object. Python Program manipulate Data Objects.
* Scalar and Non Scalar Objects.(Scalar: Very Basic Objects, Cannot be Divided(int,float,bool,none type) and Non Scalar:Can be Divided(Set, Tuples))
* Type Conversion-Casting: Can convert object of one type to another: Take care of this in python, used in multiple places.
* Operator Precedence - PEMDAS
* Variables: Keep a descriptive name and put some values into it. No need to specify the data type. Python is dynamically typed language.

[PSET 0](https://gist.github.com/riya1606/648df233ad888c5fe51450cf74edbff6)

### Lecture 2: Branching and Iteration
* Strings
* input()- this gives you string so you must cast it. int(input("Enter a Number"))
* Comparison Operator used on Strings (Lexiographical Order), int and float. This evaluates to a Boolean (>,<,>=,<=,==,!=).
* Logical Operators on booleans. (and,or,not)
* Control Flow - Branching:
    * if
    * elif
    * else 
* Indentation
* Control Flow - Iterations:
    * While Loop
    * For Loop --> range(start,stop,step)
    * break statement

### Lecture 3: String Manipulation, Guess and Check, Approximations, Bisection
* String Manipulation
    * len()
    * indexing
    * slicing [start:stop:step]
    * Strings are Immutable. Cannot be modified.
    * for loop in string
* Algorithms
    * Guess and Check
    * Approximations
    * Bisection Search (Within 6 guesses).


### Lecture 4: Decomposition, Abstractions, Functions	
* Good Programming
* Decomposition using Functions
* Abstraction
* Function Characteristic
* Variable Scope
* Function as Argument


### Lecture 5: Tuples, Lists, Aliasing, Mutability, Cloning	
* Tuples
    * Immutable 
    * Indexing
    * Concatenation
    * Slicing
    * len()
    * Can be used to swap variables conveniently
    * To return multiple data from function as function can return only one object
    * Iteration can be done over tuple
* Lists
    * Mutable 
    * Indexing
    * len()
    * Slicing
    * Change Elements- Lists are Mutable
    * Iterating over a list
    * .append()
    * Concatenate
    * del()
    * pop()
    * remove()
    * sort()
    * sorted()
    * remove()
* Converts List to String and String to List
    * String to List: list(s)--> Every character from S an element in L
    * String to List: s.split()--> To split a string on a character parameters(default:spaces)
    * List to String: L.join()--> To turn a list into characters in a string (''.join(L)="abc" |||| '_'.join(L)="a_b_c")
* Aliasing- Changing one changes the other
* Mutability [:]
* Cloning

### Lecture 6: Recursion, Dictionaries	
* Recursion
    * Algorithmically: Divide and Conquer
    * Semantically: Function calls itself 
    * Each Recursive Call to a function creates its own Scope/Environment
    * Tower of Hanoi
    * Fibonacci Numbers
    * Recursion on Non- Numeric: Palindrome
* Dictionaries
    * Associates key to a value
    * {}
    * Add: dictionary_name['key']=value
    * Test: 'key' in Dictionary 
    * Delete: del(Dictionary_name['key'])
    * dictionary.key()--> gives all keys in no specific order
    * dictionary.value()--> gives all value in no specific order
    * Inefficient Fibonacci can be made efficient using Dictionaries
### Lecture 7: Testing, Debugging, Exceptions, Assertions	
* Aim for High Quality: Analogy with Soup
* Testing
    * Unit Testing
    * Regression Testing
    * Integration Testing
    * Random Testing
    * Black Box Testing
    * Glass Box Testing
* Debugging
* Error Messages
* Exceptions:
    * try
    * except 
    * else
    * finally
    * raise
* Assertions   

### Lecture 8: Object Oriented Programming	
* Object
* OOP and Advantages of OOP
* Creating and Using Classes
* Define classes: data instances and methods or behaviour
* Special Operators

### Lecture 9: Python Classes and Inheritance	
* Write code from two Perspective: Implementing the Class, Using the Class
* Class Definition of an object type and Instance of Class
* Use of Object Oriented Programming
* Getter and Setter
* Information Hiding
* Default Arguments
* Hierarchies
* Class Variables

### Lecture 10: Understanding Program Efficiency, Part 1	



### Lecture 11: Understanding Program Efficiency, Part 2	


### Lecture 12: Searching and Sorting	


# Princeton Courses
## Bitcoin and Cryptocurrency Technologies

### Day1: Intro to Crypto and Cryptocurrencies
### Day2: How Bitcoin Acheives Decentralization
### Day3: Mechanics of Bitcoin
### Day4: How to Store and Use Bitcoins
### Day5: Bitcoin Mining
### Day6: Bitcoin and Anonymity
### Day7: Community, Politics and Regulation
### Day8: Alternative Mining Puzzle
### Day9: Bitcoin as a Platform
### Day10: Altcoins and Cryptocurrency Ecosystem
### Day11: The Future of Bitcoin?


# StanfordCourses
## CS106A: Mehran Sahami
### Lecture 1:
* Introduction to the Class
* Karel the Robot and why is it used in this course.
### Lecture 2:
* Basic Karel Commands 
* Algorithm vs Programs
* Syntax of Karel Program
* Creating Methods
* Super Karel
* Loops and Conditional Statements
* Coding Testing Debugging Cycle
#### Assignment 1:
##### Problem 1:
[Solution 1](https://gist.github.com/riya1606/4c718d0d6dee650f6e3021b9c664600d)
##### Problem 2:
[Solution 2](https://gist.github.com/riya1606/b9a3dcfa809ba26bbc9783e5d29e95ec)
##### Problem 3:
[Solution 3](https://gist.github.com/riya1606/9b4670c10ab1e897356eafc7c4e23039)
##### Problem 4:
[Solution 4](https://gist.github.com/riya1606/081d8a71e2935468f29093ddc183cf1e)
### Lecture 3:
* Karel and Java
* Common Errors
* Infinite Loops and Off By One Bug (OBOB)
* Comments
* Decomposition - "Top Down Design" and "Bottom Up Design"
* The DoubleBeepers Example
* Importance of Good Software Engineering - Decomposition Indentation Comments
* The Right Decomposition 
* The CleanUp Karel Example
### Lecture 4:
* History of Computing
* Programming VS Computer Science
* Binary, HLL, LLL, Machine Language, Source Code, Object Code
* Process of Compilation
* Java as an Object Oriented Programming Language
* Inheritence : Superclass and Subclass
* Instance and Behaviour of Classes in Java
* FirstJavaProgram
* Console Program Example
* Graphic Window
* GLabel Example
### Lecture 5:
* Variables
* Data Types and Syntax (for Variables)
* Classes as Types and Object as Variables
* Invoking Methods on Objects
* Graphic Coordinates and Operation on GObject Classes and its Subclasses
* Drawing Geometrical Objects
* Expressions and Operators
### Lecture 6:
* readInt() and readDouble()
* / operator
* Operators: Order of Precedence
* Typecasting
* Shorthands used in programming
* Constants
* Booleans
* Value Comparison
* Boolean Expressions
* Short Circuit Evaluation (Very very useful)
* Statement Blocks and Scope of Variable
* Conditional (if-else, cascading if, switch-case)
* Loop (For and While)
### Lecture 7:
* The Loop and a Half Problem (Avoid Repetition of code and usage of break)
* For VS While Loop
* CheckerBoard Program Example
* Methods in Java
* Example of methods
* FactorialExample Problem
* Returning Objects from Methods
### Lecture 8:
* Information Hiding
* The Void Return Type
* Parameter Passing between Methods
* BadTimes with methods
* Using Classes
* Instance Variables vs Local Variables
* The RandomGenerator Program Example
* The RollDice Program Example
* The setSeed method()
### Lecture 9:
* Strings
* Writing your own class
* Public and Private Visibility
* Creating a New Class
* The Constructor Method
* Shadowing of variables and 'this' keyword
* Using the created class
* Objects are Called by Reference not Called by Value
* Class Variables
* The JavaDoc
* The Student Program Example
### Lecture 10:
*  Importance of Private Variables
*  Extending the Student Class
*  Overriding Methods
*  The acm.graphics Package
*  GCanvas
*  Methods Common to All GObjects
*  Interfaces and Methods Defined by Them
*  The BouncingBall Program Example
*  The Geometry of the GLabel Class
*  The GArc Class


## CS229: Andrew Ng
### Lecture 1:


## CS255: Dan Boneh
### Lecture 1:
