# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
x=16
y=bin(x)
print(y)
```
## Output
![WhatsApp Image 2025-05-15 at 10 08 39_2b8838ac](https://github.com/user-attachments/assets/92a25452-ef4e-43f2-ac89-e70b5f2ddedc)

## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.

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
```
def result(a,b):
    a=a%b
    return a
a=int(input())
b=int(input())
result1=result(a,b)
print("modulo is",result1)
```
## Output
![WhatsApp Image 2025-05-15 at 10 14 02_c7daf21a](https://github.com/user-attachments/assets/f35a719a-9738-4f3e-b96e-eb91b999e506)

## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
i=int(input())
j=int(input())

f = lambda a, b: a+b

print(f(i, j))
```

## Output
![image](https://github.com/user-attachments/assets/48251c03-8a21-4a12-945f-73e45b2c2a7d)

## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b returns their sum is created successfully.

## Looping(Patterns)-Pascal's Triangle Generator in Python

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
Add Code Here
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
```

## Sample Output
![image](https://github.com/user-attachments/assets/1ed81c85-5c4c-45fa-9e33-7cae22ab04cb)

## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

## Loops in Python: Palindrome Number Checker

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
Add code Here
```
num=int(input())
temp=num
rev=0
while temp>0:
    digit=temp%10
    rev=rev*10+digit
    temp=temp//10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```
## Output
![WhatsApp Image 2025-05-15 at 10 39 44_73c5da7b](https://github.com/user-attachments/assets/7baa4308-893e-422f-94b9-b22798dc5d9a)

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
