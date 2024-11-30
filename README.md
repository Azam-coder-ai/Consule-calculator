# Consule-calculator
print('<<<Consule calculator>>>')
a = float(input('Enter the number: '))
use = input("'*' '-' '+' '/' '%'\nUse these operators: ")
b = float(input('Enter the number: '))
if use == '*':
    result = a*b
elif use == '/':
    result = a/b
elif use == '-':
    result = a-b
elif use == '+':
    result = a+b
print(f"Output: {result}")

