[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15344761&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms and is widely used in web development, data analysis, artificial intelligence, scientific computing, and more.

Key Features:

Simple and easy-to-read syntax.

Extensive standard library.

Dynamically typed with automatic memory management.

Strong community support and large ecosystem of third-party libraries.

Use Cases:

Web development (Django, Flask).

Data analysis and visualization (Pandas, Matplotlib).

Machine learning and AI (TensorFlow, PyTorch).

Automation and scripting.

2. Installing Python:

Windows: Download the installer from python.org, run it, and select "Add Python to PATH" during installation.

macOS: Python is pre-installed on macOS, but you can install a newer version using Homebrew (brew install python).

Linux: Use your package manager (apt, yum, etc.) to install Python (sudo apt-get install python3 for example).

Verify Installation: Open a terminal or command prompt and type python --version or python3 --version.

Setting up a Virtual Environment: Use venv or virtualenv module (python -m venv myenv), activate it, and install packages (pip install package).

3. Python Syntax and Semantics:

print("Hello, World!")

Syntax Elements:

print(): Function to output text to the console.

"Hello, World!": String literal enclosed in double quotes.

4. Data Types and Variables:

Basic Data Types: Integer (int), Float (float), String (str), Boolean (bool), List (list), Tuple (tuple), Dictionary (dict).

Example Script:

Variables of different data types

num1 = 10      # int

num2 = 3.14    # float

name = "Alice" # str

is_valid = True # bool

5. Control Structures:

Conditional Statements:

if-else statement

num = 10

if num > 0:

   print("Positive")

else:

   print("Non-positive")

Loops:

for loop

for i in range(1, 5):

   print(i)

6. Functions in Python:

Function Definition:

Function to calculate sum of two numbers

def add_numbers(a, b):

    return a + b



Calling the function

result = add_numbers(3, 5)

print("Sum:", result)

7. Lists and Dictionaries:

Lists: Ordered collection of items.

Dictionaries: Key-value pairs, unordered.

List

numbers = [1, 2, 3, 4, 5]


Dictionary

person = {"name": "Alice", "age": 30, "city": "New York"}


Accessing elements

print(numbers[0])       # Prints 1

print(person["name"])   # Prints "Alice"

8. Exception Handling:

Try-Except-Finally Blocks:


Handling division by zero exception

try:

    result = 10 / 0

except ZeroDivisionError:

    print("Error: Division by zero!")

finally:

    print("Execution complete.")

9. Modules and Packages:

Modules: Python files containing definitions and statements.

Packages: Collection of modules.


Importing and using math module

import math


Calculating square root

num = 25

sqrt_value = math.sqrt(num)

print("Square root of", num, "is", sqrt_value)

10. File I/O:

Reading and Writing Files:


Reading from a file

with open("data.txt", "r") as file:

    content = file.read()

    print(content)

Writing to a file

data = ["Apple", "Banana", "Orange"]

with open("output.txt", "w") as file:

    for fruit in data:

      file.write(fruit + "\n")

# Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.

- Provide code snippets or complete scripts where applicable.

- Cite any references or sources you use in your answers.

- Submit your completed assignment by [due date].


