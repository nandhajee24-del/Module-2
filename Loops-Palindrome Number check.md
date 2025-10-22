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
 
