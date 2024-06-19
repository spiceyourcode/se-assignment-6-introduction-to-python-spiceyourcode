[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15297984&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   - Python is a high-level, interpreted programming language known for its simplicity and readability.
   - Web Development: Frameworks like Django and Flask are popular for building web applications.
   Data Science: Python is widely used for data manipulation, analysis, and visualization with libraries such as Pandas, NumPy, and Matplotlib.
   Machine Learning and AI: Libraries like TensorFlow, PyTorch, and scikit-learn make Python a preferred language for machine learning and artificial intelligence.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   - Download Python:

   Go to the official Python website: python.org.
   Navigate to the Downloads section and download the installer appropriate for your operating system (Windows, macOS, or Linux). for my case its windows 
   Run the Installer:

   Execute the downloaded installer.
   Check the option "Add Python to PATH" during installation on Windows to easily run Python from the command line.
   Verify Installation:

   Open a terminal (command prompt on Windows) and type python --version
   This should display the installed Python version.
   Set Up a Virtual Environment:

   Virtual environments are recommended to isolate dependencies for different projects.
   Install virtualenv if it's not already installed: pip install virtualenv.
   Create a new virtual environment: python -m venv myenv.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   - print("Hello, World!")
   -  This is a built-in Python function that outputs the given message to the console.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   - int: Integer numbers.
   float: Floating-point numbers.
   str: Strings of characters.
   bool: Boolean values.
   # Creating and using variables of different data types
   my_integer = 42
   my_float = 3.14
   my_string = "Hello, Python!"
   my_boolean = True

   # Printing variables to console
   print(my_integer)
   print(my_float)
   print(my_string)
   print(my_boolean)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   - # Example of if-else statement
   x = 10

   if x > 5:
      print("x is greater than 5")
   else:
      print("x is not greater than 5")
      # Example of for loop
   for i in range(5):
      print(i)



1. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   - Functions in Python are blocks of organized, reusable code used to perform a single, related action.
   - # Function that takes two arguments and returns their sum
   def add_numbers(a, b):
      return a + b

   # Calling the function
   result = add_numbers(5, 3)
   print("Sum:", result)  # Output: Sum: 8


2. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
 - Lists: Ordered collection of items ([1, 2, 3, 4, 5]).
   Dictionaries: Key-value pairs ({"name": "Alice", "age": 30, "city": "New York"}).

   # Creating a list of numbers
   my_list = [1, 2, 3, 4, 5]

   # Creating a dictionary with key-value pairs
   my_dict = {"name": "Alice", "age": 30, "city": "New York"}

   # Basic operations on list
   print("Length of list:", len(my_list))
   print("First element of list:", my_list[0])

   # Basic operations on dictionary
   print("Value for key 'name':", my_dict["name"])
   print("Keys in dictionary:", list(my_dict.keys()))



3. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   - Allows handling of errors or exceptions that may occur during program execution.
   - # Example of try-except-finally blocks
   try:
      x = 10 / 0  # This will raise a ZeroDivisionError
   except ZeroDivisionError as e:
      print("Error:", e)
   finally:
      print("Execution completed")


4. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   - Modules are Python files containing functions, classes, and variables. Packages are directories of Python modules.
   - # Example of importing and using the math module
   import math

   print("Value of pi:", math.pi)
   print("Square root of 16:", math.sqrt(16))


5.  File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    - # Reading content of a file and printing it to console
   with open("example.txt", "r") as file:
      content = file.read()
      print(content)
      # Writing a list of strings to a file
      lines = ["First line\n", "Second line\n", "Third line\n"]

      with open("output.txt", "w") as file:
         file.writelines(lines)




# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


