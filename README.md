# PYTHON MODULE-2 
## NAME: PREETHI D
## REGISTER NUMBER: 212224040250

# EXP 01 - Built-in Functions -Binary Conversion Using Built-in Functions in Python

##  Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

##  Program
```
a = 16
binary = bin(a)
print(binary)
```
## Output
![image](https://github.com/user-attachments/assets/1455fdc3-9c43-4e24-a319-6de6b96333c4)

## Result
Therefore the given Python program has been executed successfully and the output has been verified.

# EXP 02 -  Functions in Python: Modulo Calculator

##  Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

##  Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

##  Program
```
a = int(input())
b = int(input())
c = a % b
print(c)
```

## Output
![image](https://github.com/user-attachments/assets/c8f58c18-0573-4921-b589-8f336ab6adab)

## Result
Therefore the given Python program has been executed successfully and the output has been verified.

# EXP03 - Lambda Function in Python: Addition of Two Numbers

##  Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

##  Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

##  Program
```
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

f = lambda x, y: x + y
result = f(a, b)
print("The sum is:", result)
```

## Output
![image](https://github.com/user-attachments/assets/549fdda6-a3e3-4d31-847a-7e1ebc840a4a)

## Result
Therefore the iven Python program has been executed successfully and the output has been verified.

# EXP 04 - Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

##  Aim
To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.
##  Algorithm

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

##  Program
```
import math

rows = int(input("Enter the number of rows for Pascal's Triangle: "))

for n in range(rows):
    print(' ' * (rows - n - 1), end='')

    for k in range(n + 1):
        value = math.comb(n, k) 
        print(value, end=' ')

    print()
```
## Sample Output
![image](https://github.com/user-attachments/assets/140af27c-497c-4c61-bd71-cf15a7b51a6a)

## Result
Therefore the given Python Program has been executed successfully and the output has been verified.
