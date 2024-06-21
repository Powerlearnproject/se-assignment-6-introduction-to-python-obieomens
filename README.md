[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15305102&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level, interpreted programming language known for its simplicity and readability.

Key Features of Python are.

Readability and Simplicity:
Python's syntax is clean and easy to understand, making it an ideal language for beginners and for rapid development.

Interpreted Language:
Python is an interpreted language, meaning that code is executed line-by-line, which makes debugging easier and faster.

Dynamically Typed:
Variables in Python do not need explicit declaration to reserve memory space. The declaration happens automatically when a value is assigned to a variable.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   
   Steps to Install Python on Linux
   sudo apt update.
   sudo apt install software-properties-common
   sudo apt install python3.10
   Python3.10 --version (to check if python is installed)
   
   to activate the virtual enviroment use the following command:
   sudo apt install python3.10-venv
   python3.10 -m venv myenv
   source myenv/bin/activate  (to activate your env).
   deactivate (to deactivate your env).

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print("Hello, World!");
   In this case, print("Hello, World!") calls the print function and passes the string "Hello, World!" as an argument.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic data types in python.
   1. Integers (int) eg.
   age = 30
   print(age)

   2. String (str):
   name = "Joe"
   print(name)

   3. List:
   fruits = ["apple", "mango", "orange"]
   print(fruits)

   4. Boolean: 
   is_student = True
   print(is_student)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Conditional statements are used to execute code based on certain conditions. The most common conditional statements in Python are if, elif, and else
   if-else example;
   name = Joe
   if name == Joe:
   print("Joe")
   else: 
   print("no name found")

   "for" example.
   for i in range (5):
   print(i)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions in Python
Functions in Python are blocks of reusable code that perform a specific task. They help to organize code into manageable sections, improve readability, and allow for code reuse. Functions can take arguments, perform operations, and return values.

Benefits of Using Functions:
Code Reusability: Write once, use multiple times.
Modularity: Break down complex problems into simpler pieces.
Readability: Make code easier to understand and maintain.
Abstraction: Hide the details and expose only the necessary parts of the functionality.

   def sum(a, b):
   return a + b

   call the function
   result = sum(4, 6)
   print(result).


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Differences Between Lists and Dictionaries in Python
Lists:
Definition: Lists are ordered collections of items that can contain any data type.
Access: Accessed by index, which starts at 0.
Mutability: Mutable (can be modified after creation).
Syntax: Enclosed in square brackets [ ].
Example: numbers = [1, 2, 3, 4, 5]
Dictionaries:
Definition: Dictionaries are unordered collections of key-value pairs.
Access: Accessed by keys, which are unique within the dictionary.
Mutability: Mutable (can be modified after creation).
Syntax: Enclosed in curly braces { }, with key-value pairs separated by colons :.


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Exception handling in Python allows you to gracefully manage and respond to errors or exceptions that may occur during program execution. It helps prevent your program from crashing abruptly and provides a way to handle unexpected situations.

try: Contains code that might throw an exception.
except: Handles specific exceptions raised in the try block.
finally: Always executes, regardless of whether an exception occurred.

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Modules in Python are files containing Python code, usually with functions, classes, and variables defined to perform specific tasks.
Modules: Individual Python files containing code for specific tasks.
Packages: Directories containing multiple modules and sub-packages, structured with __init__.py files.
Importing: Use import module_name to import a module, and access its functions/variables with module_name.item_name.

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


