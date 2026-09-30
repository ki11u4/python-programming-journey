Here are clear, hands-on Python examples demonstrating each topic in Module 2.

---

## 1. Data Types Examples

Python determines data types automatically based on how you write the value. You can use the `type()` function to inspect a value's data type.

```python
# Integer (int)
count = 10
print(type(count))  # Output: <class 'int'>

# Floating-Point (float)
price = 19.99
print(type(price))  # Output: <class 'float'>

# String (str)
message = "Hello, Python!"
print(type(message))  # Output: <class 'str'>

# Boolean (bool)
is_active = True
print(type(is_active))  # Output: <class 'bool'>

```

---

## 2. Variables & Type Casting Examples

Variables store data for reuse. Because `input()` always returns text, you often need to **type cast** (convert) strings into numbers before performing calculations.

```python
# Valid variable names (snake_case is standard in Python)
user_age = 25
item_price = 4.50
total_items = 3

# Invalid names (Uncommenting these will raise SyntaxErrors):
# 2nd_place = "Gold"   # Error: cannot start with a digit
# user-name = "Alex"   # Error: hyphen not allowed (interpreted as minus)
# class = "Math"       # Error: 'class' is a reserved keyword

# Type casting example
age_string = "25"
age_number = int(age_string)  # Converts string "25" to integer 25
print(age_number + 5)  # Output: 30

```

---

## 3. Operators Examples

### Arithmetic Operators

```python
a = 15
b = 4

print(a + b)  # Addition -> Output: 19
print(a - b)  # Subtraction -> Output: 11
print(a * b)  # Multiplication -> Output: 60
print(a / b)  # Regular Division -> Output: 3.75 (returns a float)
print(a // b)  # Floor Division -> Output: 3 (discards decimal part)
print(a % b)  # Modulo -> Output: 3 (remainder of 15 / 4)
print(a**b)  # Exponentiation -> Output: 50625 (15 raised to power of 4)

```



```python






```

---

## 4. Basic I/O & Practical Combined Program

This example combines **`input()`**, **type casting**, **arithmetic operators**, **f-string formatting**, and **`print()`** into a simple receipts calculator.

```python
# --- Basic I/O Program ---

# 1. Capture input from user (stored as strings)
item_name = input("Enter the name of the item: ")
unit_price = float(input("Enter unit price: "))  # Convert string input to float
quantity = int(input("Enter quantity purchased: "))  # Convert string input to int

# 2. Perform calculations using arithmetic operators
subtotal = unit_price * quantity
tax = subtotal * 0.08  # 8% tax rate
total = subtotal + tax

# 3. Output results using f-strings for clean formatting
print("\n--- Purchase Receipt ---")
print(f"Item: {item_name}")
print(f"Quantity: {quantity}")
print(f"Subtotal: ${subtotal:.2f}")
print(f"Tax (8%): ${tax:.2f}")
print(f"Total Due: ${total:.2f}")

