## NAME: DEEPAK.V
## REGISTER NO: 212225230044

## EX 6:Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a = 16

print(f"Binary representation of {a} is: {bin(a)}")
```
## Output

<img width="531" height="188" alt="{450F4010-5BC6-4507-A381-176B089198E4}" src="https://github.com/user-attachments/assets/7e3794d1-a574-43c8-9aef-7cfe810ad226" />

## Result
Thus, the Python program to convert the number 16 into its binary representation using the built-in bin() function was successfully implemented and executed, and the output was verified.

## EX 7:Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    print(f"The modulo of {a} and {b} is: {a % b}")

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

result(a, b)
```
## Output

<img width="423" height="241" alt="{E6ACED8F-BAE8-4F5D-A27C-8A06E58C4405}" src="https://github.com/user-attachments/assets/59d7ee4b-bf33-478a-b768-b9096a4f28f7" />

## Result
Thus, the Python program to find the modulo of two numbers using a user-defined function was successfully implemented and executed, and the output was verified.

## EX 8:Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

f = lambda a, b: a + b

print(f"The sum of {a} and {b} is: {f(a, b)}")
```
## Output

<img width="488" height="236" alt="{24A7D207-4243-4989-9378-56F934151F41}" src="https://github.com/user-attachments/assets/f1694b5c-5d47-45c7-91d3-2233f82079b6" />

## Result
Thus, the Python program using a lambda function to find the sum of two numbers was successfully implemented and executed, and the output was verified.

## EX 9:🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

## 🎯 Aim
To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

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

## 🧪 Program
```
rows = int(input("Enter the number of rows: "))

print(f"Pascal's Triangle for {rows} rows is:")

for i in range(rows):
    print(" " * (rows - i), end="")
    
    num = 1
    for j in range(i + 1):
        print(f"{num} ", end="")
        num = num * (i - j) // (j + 1)
    
    print()
```
## Sample Output

<img width="494" height="342" alt="{35532963-D816-4392-ADCB-325DF43D3CC8}" src="https://github.com/user-attachments/assets/ce639780-c7f8-40b4-9be7-fb7af8e7f9fe" />

## Result
Thus, the Python program to generate Pascal’s Triangle for a user-defined number of rows was successfully implemented and executed, and the output was verified.

## EX 10:Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input("Enter a number: "))

temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10

if rev == num:
    print(f"{num} is a palindrome number")
else:
    print(f"{num} is not a palindrome number")
```
## Output

<img width="427" height="221" alt="{EE54CF50-C3E9-430A-A4AC-9E35602AAAE6}" src="https://github.com/user-attachments/assets/8d9fb03c-5aef-468f-ada3-0dea75c25bb7" />

<img width="453" height="195" alt="{D670CBFB-26CD-46F1-9479-BADCF19C9DB7}" src="https://github.com/user-attachments/assets/3416b5a7-b9e4-498d-bb25-a87e726441a6" />

## Result
Thus, the Python program to check whether a given number is a palindrome using loops was successfully implemented and executed, and the output was verified.
