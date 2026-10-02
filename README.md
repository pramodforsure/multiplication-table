Python Multiplication Table

A beginner-friendly Python program that generates the multiplication
table for a number entered by the user.

About the Project

I am a freshman undergraduate learning Python. This is one of my early
Python practice projects, created to understand:

User input

Variables

int() for converting input into an integer

for loops

range()

f-strings

Basic arithmetic

Printing formatted output

How It Works

The program asks the user to enter a number.

The input is converted into an integer.

A for loop runs from 1 to 10.

The program multiplies the entered number by each value.

The results are displayed as a multiplication table.

Example

If the user enters:

enter your number: 7

The program produces:

7 * 1 = 7
7 * 2 = 14
7 * 3 = 21
...
7 * 10 = 70

Code

number = int(input("enter your number:"))

for i in range(1, 11):
    print(f"{number} * {i} = {number*i}")

Concepts Learned

1. User Input

input("enter your number:")

This allows the user to enter a value.

2. Integer Conversion

int(...)

The input from input() is converted into an integer so it can be used
in multiplication.

3. For Loop

for i in range(1, 11):

The loop repeats the code for values from 1 through 10.

4. F-String

f"{number} * {i} = {number*i}"

The f-string makes it easy to insert variables and calculations directly
into the output.

Requirements

Python 3.x

No external libraries are required.

How to Run

Open a terminal in the project folder and run:

python "multiplication table.py"

Then enter any whole number when prompted.

Learning Status

Level: Beginner
Project Type: Python Practice Project
Focus: Loops, input, arithmetic, and formatted output

Future Improvements

Possible improvements as I continue learning Python:

Allow the user to choose the starting and ending multiplier.

Add input validation.

Generate tables for multiple numbers.

Put the multiplication-table logic inside a function.

Create a simple menu-driven version.

Author

A freshman undergraduate learning Python and building small projects to
develop programming fundamentals.
