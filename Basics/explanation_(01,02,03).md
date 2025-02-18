# 🚀 Python Basics: First Steps  

This document explains **three foundational Python programs** covering:  
✅ Printing messages  
✅ Taking user input  
✅ Performing simple arithmetic  

---

# 📌 1️⃣ Hello World & User Input**  

🔹 Code:
```python
# Printing a welcome message
print("Hello, World! 🚀")

# Taking user input
name = input("What's your name? ")
print(f"Nice to meet you, {name}! Welcome to Python programming.")

🔹 Explanation:
✅ print() is used to display output.
✅ input() allows the user to enter their name, stored in the name variable.
✅ f"" is a formatted string used to personalize the message.


📌 2️⃣ Taking User Input for Numbers

🔹 Code:
# Taking two numbers from the user
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

print(f"You entered {num1} and {num2}.")

🔹 Explanation:
✅ input() gets user input as a string, so int() is used to convert it to an integer.
✅ The program stores and prints the two numbers.


📌 3️⃣ Simple Arithmetic Operations

🔹 Code:
# Taking two numbers and performing arithmetic
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum_result = a + b
diff_result = a - b
product_result = a * b
quotient_result = a / b  # Regular division
floor_div_result = a // b  # Floor division
modulus_result = a % b  # Modulus operation

print(f"Sum: {sum_result}")
print(f"Difference: {diff_result}")
print(f"Product: {product_result}")
print(f"Quotient: {quotient_result}")
print(f"Floor Division Result: {floor_div_result}")
print(f"Modulus Result: {modulus_result}")


🔹 Explanation:
✅ + for addition, - for subtraction, * for multiplication
✅ / gives a float result, while // performs integer division
✅ % returns the remainder of a division operation

🎯 Try These Challenges

1️⃣ Modify the arithmetic program to calculate the square and cube of a number.
2️⃣ Extend the input program to ask for a user’s age and print a custom message.
3️⃣ Change the arithmetic program to find the remainder (%) of two numbers.

Happy Coding! 🚀🔥