Welcome to Module 2! This is where programming starts to feel real—moving from basic concepts into writing code that actually stores data, performs math, and talks to users.

Here is a breakdown of what you'll be covering in this module:

---

## 1. Data Types

Python automatically categorizes the kind of data you work with. The main fundamental types include:

* **Integers (`int`)**: Whole numbers, positive or negative, without decimals (e.g., `42`, `-7`).
* **Floating-Point Numbers (`float`)**: Numbers with decimal points (e.g., `3.14`, `-0.5`).
* **Strings (`str`)**: Text enclosed in single, double, or triple quotes (e.g., `'Hello'`, `"Python"`).
* **Booleans (`bool`)**: Logical values representing truth: either `True` or `False`.

---

## 2. Variables

Variables are named containers used to store data in memory so you can use and change it throughout your program.

* **Assignment**: Use the `=` operator to assign a value to a variable (e.g., `age = 25`).
* **Naming Rules**:
* Must start with a letter or an underscore `_`.
* Cannot start with a number.
* Can only contain alphanumeric characters and underscores (`a-z`, `A-Z`, `0-9`, `_`).
* Case-sensitive (`age`, `Age`, and `AGE` are three different variables).
* Cannot use Python keywords/reserved words (e.g., `for`, `if`, `class`).



---

## 3. Operators

Operators perform operations on variables and values.

* **Arithmetic Operators**:
* Addition (`+`), Subtraction (`-`), Multiplication (`*`), Division (`/` — always returns a float).
* Floor Division (`//` — divides and rounds down to the nearest integer).
* Modulo (`%` — returns the remainder of a division).
* Exponentiation (`**` — raises a number to a power).


* **Comparison Operators**: Return a boolean (`True` or `False`).
* `==` (Equal to), `!=` (Not equal to)
* `>`, `<`, `>=`, `<=`


* **Logical Operators**: Combine conditional statements.
* `and` (True if both conditions are true)
* `or` (True if at least one condition is true)
* `not` (Reverses the boolean result)



---

## 4. Basic Input / Output (I/O)

Programs need to receive input from users and display output back to them.

* **Output (`print()`)**:
* Displays text or variable values on the screen.
* Supports formatting using string concatenation (`+`), f-strings (`f"Hello, {name}"`), or separation arguments (`sep`, `end`).


* **Input (`input()`)**:
* Prompts the user to type something and press Enter.
* **Crucial Detail**: `input()` *always* returns data as a string (`str`). If you need to do math with user input, you must cast/convert it to an integer or float first (e.g., `age = int(input("Enter your age: "))`).



---

Check the practical file to access some practical concepts 

