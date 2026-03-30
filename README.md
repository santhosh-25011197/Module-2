# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

a=16 

print(bin(a))

## Output

<img width="526" height="248" alt="image" src="https://github.com/user-attachments/assets/c6e22536-fb24-40a6-8bfe-f6f21e498c8b" />


## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.


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

<img width="615" height="292" alt="image" src="https://github.com/user-attachments/assets/52d0e026-fb26-4052-8149-93d71f83df3f" />


## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program

a=int(input()) 

b=int(input()) 

f=lambda a,b: a+b 

print(f(a,b))

## Output


<img width="428" height="176" alt="image" src="https://github.com/user-attachments/assets/27e52409-ba55-45de-bbf1-d14903ef6f62" />


## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.


# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program

def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)

def combination(n, k):
    return factorial(n) // (factorial(k) * factorial(n - k))

num_rows = int(input("Enter number of rows: "))

for i in range(num_rows):
    print(' ' * (num_rows - i - 1), end='')
    for j in range(i + 1):
        print(combination(i, j), end=' ')
    print()

## Sample Output


<img width="202" height="220" alt="image" src="https://github.com/user-attachments/assets/417e7fc9-2596-4cf1-af62-d04994874c6a" />

## Result

Thus,the program was implemented and executed successfully,and the required output was obtained.
