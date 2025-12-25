# Functions in Python: Modulo Calculator

## 🎯 Aim
Write a python program to define a function that accepts 2 values and return its sum, subtraction and multiplication.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the sum using `a + b`, subtraction using `a - b`,multiplication using `a*b`
3. Print the result of the sum,sub and mul operations.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

def result(a,b):
    sum = a+b
    sub = a-b
    mul = a*b
    return f"Sum is {sum}, Sub is {sub}, & Multiply is {mul}"

a = int(input())
b = int(input())
print(result(a,b))

## Output
<img width="990" height="306" alt="image" src="https://github.com/user-attachments/assets/25c81c40-adba-4df0-8c67-22e620029014" />

## Result
Thus a python program to define a function that accepts 2 values and return its sum, subtraction and multiplication is created.
