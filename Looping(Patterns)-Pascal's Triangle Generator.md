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
