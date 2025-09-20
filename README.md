# Factorial.pycode
Factorial of a number 
# Simple Python program to solve factorial of a number

def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)

# Input
num = int(input("Enter a number: "))

# Output
print("Factorial of", num, "is:", factorial(num))

