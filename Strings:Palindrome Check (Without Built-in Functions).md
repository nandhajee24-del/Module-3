# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```py
# Step 1: Assign the string
s = "google"

# Step 2: Reverse the string using slicing
rev = s[::-1]

# Step 3: Compare and print result
if s == rev:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output
<img width="398" height="48" alt="Screenshot 2025-10-22 212451" src="https://github.com/user-attachments/assets/4bd74ec5-48c0-4d1f-ab9c-2dc4577bdcc6" />

## Result
successfully  Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions. 
