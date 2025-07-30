# Assignment-3
#Task 1: Calculate Factorial Using a Function
num = int (input("Enter a number: "))
def factorial(num):
    if (num<2):
        return 1
    else:
        return (num*(factorial(num-1)))
result = factorial(num)
print(f"Factorial of {num} is:",result)


#Task 2: Using the Math Module for Calculations
a = int (input("Enter a number: "))
from math import *
print("Square root: ",sqrt(a))
print("Logarithm: ",log(a))
print("Sine: ",sin(a))
