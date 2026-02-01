result = add_numbers(5, 3)
print(f"The sum is: {result}")

This Python script defines two functions: `welcome_message()` that prints a greeting and `add_numbers(a, b)` which returns the sum of two numbers. The script calls `welcome_message()`, adds two numbers using `add_numbers(5, 3)`, and prints the result. It serves as a basic example to demonstrate function definitions and usage in Python.

## Change Log
* **2026-02-01 (Update)**: File: utils.py
Changes:
@@ -1,3 +1,4 @@
 def welcome_message():
     print("Welcome to the program!")
+    return "Welcome to the program!"

File: requirements.txt
Changes:
@@ -1,1 +1,2 @@
 numpy
+matplotlib

The code was updated to add a new feature in `main.py` that prints a new feature message, modify `utils.py` to have the `welcome_message` function return a string, and add

* **2026-02-01**: File: utils.py
Changes:
@@ -2,3 +2,3 @@ def calculate_sum(numbers):
     return sum(numbers)
 
-def get_average(numbers):
+def get_average(numbers=[]):
     return sum(numbers) / len(numbers)

- Fix a bug in get_average function by setting a default value for the numbers parameter
- Add a new feature in main.py to print a welcome message

* Enhanced `main.py` and `utils.py` by adding a new feature to print a welcome message in `main.py`, and improving the `get_average` function in `utils.py` by setting a default value for the `numbers` parameter to handle potential bugs.