# Simple Calculator Program

Everyone's first Python project be like 😂

This program asks for two numbers and shows:
- Addition
- Subtraction
- Multiplication
- Division (with error if divide by zero)

## How to Run
1. Copy the code below.
2. Paste in VS Code or online Python editor (like replit.com).
3. Run it!

## The Code
```python
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

print("The addition is:", a + b)
print("The subtraction is:", a - b)
print("The multiplication is:", a * b)

if b != 0:
    print("The division is:", a / b)
else:
    print("Error: Cannot divide by zero!")
