# everyone-s-first-python-project-be-like

# Simple Calculator Program
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

    # Always show addition, subtraction, multiplication
print("The addition is:", a + b)
print("The subtraction is:", a - b)
print("The multiplication is:", a * b)
    
    # Only divide if b is not zero
if b != 0:
        print("The division is:", a / b)
else:
        print("Error: Cannot divide by zero!")
