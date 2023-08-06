# Python

Introduction to Computer Programming:

Computer programming is the process of writing instructions (code) that a computer can understand and execute to perform specific tasks. Programming allows us to create software, applications, and games, among other things. It involves breaking down a problem into smaller steps and then using a programming language to express those steps in a way that a computer can follow.

Python as a Programming Language:

Python is a high-level, interpreted, and general-purpose programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991. Python's design philosophy emphasizes code readability and a clean syntax, making it easier to write and understand. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming

Python Data Types:

In Python, data types represent the kinds of values that variables can hold. Some of the commonly used data types in Python are:

    Integer: Represents whole numbers like 1, 2, -5, etc.
    Float: Represents floating-point numbers with decimal places, like 3.14, 2.5, etc.
    String: Represents a sequence of characters enclosed in single or double quotes, like "hello," "world," etc.
    Boolean: Represents the values True or False, used in logical operations.

Variables and Assignments:

Variables are used to store data in a program. They act as containers that hold values of different data types. In Python, you can declare a variable and assign a value to it using the equal sign (=). For example:

`
age = 25
name = "John"
`

Comments and Expressions:

Comments are used to add explanatory notes to the code and are ignored by the interpreter when the program runs. In Python, comments start with the hash symbol (#). For example:

`# This is a comment
`
Expressions are combinations of variables, values, and operators that are evaluated to produce a result. Python supports various arithmetic, comparison, and logical operators that can be used in expressions.

Control Structures:
Control structures allow you to control the flow of a program. The most common control structures are:

    If statements: Used for conditional execution of code based on a specific condition.
    If-else statements: Used to execute one block of code if a condition is true and another block if it's false.

Looping and Branching:
Loops allow you to repeat a block of code multiple times until a certain condition is met. Python supports two types of loops:

    While loop: Repeats a block of code as long as a specified condition is true.
    For loop: Iterates over a sequence (like a list) and executes the block of code for each item in the sequence.

`# Create variables for your name, age, and favorite hobby. Print a message using these variables.
name = "John"
age = 25
hobby = "playing guitar"
print(f"My name is {name}, I am {age} years old, and my favorite hobby is {hobby}.")
`

`# Calculate the area of a rectangle given its length and width.
length = float(input("Enter the length of the rectangle: "))
width = float(input("Enter the width of the rectangle: "))
area = length * width
print("The area of the rectangle is:", area)
`

`
# Convert Celsius to Fahrenheit
celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print("Temperature in Fahrenheit:", fahrenheit)
cel = (fahrenheit - 32) * 5/9
print("Temperature in Celsius:", cel)

# Simple Calculator
num1 = float(input("Enter the first number: "))
operator = input("Enter the operator (+, -, *, /): ")
num2 = float(input("Enter the second number: "))

if operator == "+":
    result = num1 + num2
elif operator == "-":
    result = num1 - num2
elif operator == "*":
    result = num1 * num2
elif operator == "/":
    result = num1 / num2
else:
    print("Invalid operator")
    exit()

print("Result:", result)
# Print the first 10 even numbers using a while loop
count = 1
while count <= 10:
    if count % 2 == 0:
        print(count)
    count += 1
fruits = ["Apple", "Orange", "Watermelon", "Grapes", "pomegranate"]
print(fruits[-1])
print(fruits[:-1])
print(fruits[2:5])
print(fruits[2])
print(fruits[3:])

squares = [num**2 for num in range(1, 11)]
print(squares)

# Find common elements between two lists.
list1 = [1, 2, 3, 4, 5]
list2 = [4, 5, 6, 7, 8]
common_elements = [elem for elem in list1 if elem in list2]
print("Common elements:", common_elements)


`











