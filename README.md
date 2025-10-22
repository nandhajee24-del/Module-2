Nandha A(25017364)

# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```py

a = 16
binary_value = bin(a)
print("Binary of", a, "is:", binary_value)
```


## Output
<img width="294" height="52" alt="Screenshot 2025-10-22 183703" src="https://github.com/user-attachments/assets/c7ee0391-ee61-4ffe-8720-f4b4607ea4d2" />

## Result
successfully Python program to convert the number **16** into its **binary representation** using built-in Python functions. 


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
```py

def result(a, b):
    print("Modulo result:", a % b)
x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))
result(x, y)
```

## Output
<img width="349" height="108" alt="Screenshot 2025-10-22 184245" src="https://github.com/user-attachments/assets/d076011e-d077-4f9f-9f61-b36dfc774160" />

## Result
successfully Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.
 


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```py

a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))
f = lambda x, y: x + y

print("Sum is:", f(a, b))
```

## Output
<img width="311" height="90" alt="Screenshot 2025-10-22 184914" src="https://github.com/user-attachments/assets/5189f808-a908-4b67-bccf-dc4b22deae1e" />


## Result
successfully Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum. 


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
```pyimport math

# Step 2: Input number of rows
rows = int(input("Enter the number of rows: "))

# Step 3: Loop through each row
for i in range(rows):
    # Step 4a: Print spaces for formatting
    print(" " * (rows - i), end="")

    # Step 4b: Compute and print values using binomial coefficient
    for j in range(i + 1):
        value = math.comb(i, j)  # C(n, k) = n! / (k! * (n-k)!)
        print(value, end=" ")
    
    print()  
```
## Sample Output

<img width="365" height="160" alt="Screenshot 2025-10-22 205528" src="https://github.com/user-attachments/assets/6c5b5c7a-f65e-4d7c-baa2-f0ceea2b7238" />

## Result
successfully Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.



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
```py
# Step 1: Get input from the user
num = int(input("Enter a number: "))

# Step 2: Assign to a temporary variable
temp = num

# Step 3: Initialize the reverse variable
rev = 0

# Step 4: Reverse the digits using a while loop
while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10

# Step 5: Check if the number is a palindrome
if rev == num:
    print("The number is a palindrome.")
else:
    print("The number is not a palindrome.")
```
## Output
<img width="392" height="75" alt="Screenshot 2025-10-22 205915" src="https://github.com/user-attachments/assets/b150c157-c071-4e3a-9b07-5d239d948231" />
<img width="385" height="78" alt="Screenshot 2025-10-22 205934" src="https://github.com/user-attachments/assets/a286ce4d-204e-4d27-bc3e-472ca8522055" />

## Result
successfully  Python program that checks whether a given number is a **palindrome** using loops.
 

 
