# Subject: Python Programming (B.Tech CSE Core)

## Topic 1: Introduction to Python
Python is a high-level, interpreted, general-purpose programming language known for its simple syntax and readability. It was developed by Guido van Rossum and released in 1991. Python supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

Python is an interpreted language, which means its code is executed through an interpreter. It is dynamically typed, meaning we do not need to declare the data type of a variable explicitly. Python is widely used in web development, artificial intelligence, machine learning, data science, automation, and software development.

## Topic 2: Variables and Data Types
A variable is a named memory reference used to store data in a program. In Python, variables are created when a value is assigned using the assignment operator (=). Python does not require explicit variable declarations because it is dynamically typed.

Python has several built-in data types:
1. int: Stores integer values, such as 10, 25, and -5.
2. float: Stores decimal values, such as 3.14 and 5.5.
3. str: Stores text or sequences of characters, such as "Hello".
4. bool: Stores Boolean values, either True or False.
5. list: Stores an ordered and mutable collection of elements.
6. tuple: Stores an ordered and immutable collection of elements.
7. set: Stores an unordered collection of unique elements.
8. dict: Stores data in key-value pairs.

The type() function is used to determine the data type of a variable.

## Topic 3: Operators and Control Statements
Operators are special symbols used to perform operations on variables and values. Python supports different types of operators:
1. Arithmetic Operators: Perform mathematical operations such as addition (+), subtraction (-), multiplication (*), division (/), modulus (%), and exponentiation (**).
2. Comparison Operators: Compare two values using operators such as ==, !=, >, <, >=, and <=.
3. Logical Operators: Perform logical operations using and, or, and not.
4. Assignment Operators: Assign values using =, +=, -=, *=, and /=.
5. Membership Operators: Check whether an element exists in a sequence using in and not in.
6. Identity Operators: Check whether two objects refer to the same object using is and is not.

Control statements determine the flow of program execution. Python uses if, elif, and else for decision-making. Loops such as for and while are used to execute a block of code repeatedly. The break statement terminates a loop, continue skips the current iteration, and pass acts as a placeholder.

## Topic 4: Functions in Python
A function is a reusable block of code designed to perform a specific task. Functions help improve code reusability, readability, and modularity.

Python functions are defined using the def keyword, followed by the function name and parentheses. A function can accept parameters and return a result using the return statement.

Types of functions:
1. Built-in Functions: Predefined functions such as print(), len(), type(), input(), and sum().
2. User-defined Functions: Functions created by programmers using the def keyword.
3. Anonymous Functions: Small functions created using the lambda keyword.

Function arguments can be positional, keyword, default, or variable-length arguments. Python also supports recursion, where a function calls itself to solve a problem.

## Topic 5: Object-Oriented Programming (OOP)
Object-Oriented Programming is a programming approach based on classes and objects. It helps organize complex programs by combining data and functions into a single unit.

A Class is a blueprint or template used to create objects. An Object is an instance of a class containing data and methods.

The four main principles of OOP are:
1. Encapsulation: Wrapping data and methods together inside a class and controlling access to them.
2. Inheritance: Allowing one class to acquire the properties and methods of another class.
3. Polymorphism: Allowing the same method or interface to perform different operations depending on the object.
4. Abstraction: Hiding implementation details and showing only essential features.

The __init__() method is a constructor that initializes object attributes when an object is created. The self parameter refers to the current instance of the class.

## Topic 6: Inheritance and Its Types
Inheritance is an important feature of object-oriented programming that allows a child class to reuse the properties and methods of a parent class. It promotes code reusability and reduces code duplication.

Python supports five common types of inheritance:
1. Single Inheritance: One child class inherits from one parent class.
2. Multiple Inheritance: One child class inherits from multiple parent classes.
3. Multilevel Inheritance: A class inherits from another derived class, forming a chain.
4. Hierarchical Inheritance: Multiple child classes inherit from the same parent class.
5. Hybrid Inheritance: A combination of two or more types of inheritance.

The super() function is used to access methods and constructors of the parent class from a child class.

## Topic 7: Exception Handling
An exception is an error that occurs during program execution and interrupts the normal flow of the program. Exception handling allows programmers to manage runtime errors without terminating the entire program unexpectedly.

Python uses the following keywords for exception handling:
1. try: Contains code that may generate an exception.
2. except: Handles the exception if an error occurs.
3. else: Executes when no exception occurs in the try block.
4. finally: Executes whether an exception occurs or not.
5. raise: Used to manually generate an exception.

Common Python exceptions include ZeroDivisionError, ValueError, TypeError, IndexError, KeyError, and FileNotFoundError.

## Topic 8: File Handling in Python
File handling is used to create, read, write, and modify files using Python programs. Python provides the open() function to work with files.

Common file modes include:
1. r: Opens a file for reading.
2. w: Opens a file for writing and overwrites existing content.
3. a: Opens a file for appending new content.
4. x: Creates a new file and generates an error if the file already exists.
5. r+: Opens a file for both reading and writing.

Common file methods include read(), readline(), readlines(), write(), and close(). The with statement is recommended because it automatically closes the file after completing the operation.

## Topic 9: Python Modules and Libraries
A module is a Python file containing functions, variables, and classes that can be reused in other programs. Modules help organize code into smaller and manageable components.

Python provides built-in modules such as math, random, datetime, os, and sys. A module can be imported using the import keyword.

Libraries are collections of modules that provide additional functionality. Some important Python libraries are:
1. NumPy: Used for numerical computations and working with multidimensional arrays.
2. Pandas: Used for data manipulation and analysis.
3. Matplotlib: Used for creating graphs, charts, and visualizations.
4. Tkinter: Used for developing graphical user interfaces (GUI).
5. Scikit-learn: Used for machine learning algorithms and predictive modelling.

These libraries are widely used in artificial intelligence, machine learning, and data science.

## Topic 10: Python Applications
Python is widely used in different fields because of its simplicity, flexibility, and extensive library support.

Major applications include:
1. Artificial Intelligence: Developing intelligent systems and AI-based applications.
2. Machine Learning: Building predictive models using libraries such as Scikit-learn.
3. Data Science: Analyzing and processing large datasets using NumPy and Pandas.
4. Web Development: Creating websites and web applications using Django and Flask.
5. Automation: Automating repetitive tasks such as file management and data processing.
6. GUI Development: Creating desktop applications using Tkinter.
7. Game Development: Developing simple games using libraries such as Pygame.

Python is particularly important in modern computer science because it provides powerful tools for AI, ML, automation, and data analysis.