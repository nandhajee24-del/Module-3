# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```py
# Step 1: Define the function
def remove(s):
    # Step 2: Read the index from the user
    n = int(input("Enter the index to remove: "))
    
    # Step 3: Initialize an empty string
    a = ""
    
    # Step 4–6: Loop through the string and build the new one
    for i in range(len(s)):
        if i != n:
            a += s[i]
    
    # Step 7: Return the modified string
    return a

# Step 8: Get input string and print result
input_str = input("Enter a string: ")
print("Modified string:", remove(input_str))
```

## Output
<img width="445" height="122" alt="Screenshot 2025-10-22 212223" src="https://github.com/user-attachments/assets/3d1ca715-64eb-4422-a0a5-e8842bc4a4cb" />

## Result
successfully Python program that accepts a string and removes the character at a specified index. 
