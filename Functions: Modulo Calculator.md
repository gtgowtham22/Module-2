# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))

## Output
![438202835-14ae2269-c1f1-4530-8afc-7c13ce0aadcc](https://github.com/user-attachments/assets/a87dd9be-00ad-4e15-9aa3-ac52094b3a32)

## Result
The function was successfully defined to accept two values and return their modulo using the % operator.
