Nandha A(25017364)
# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```py
# Step 1: Define a list of numbers
numbers = [5, 10, 15, 20]

# Step 2: Use sum() to calculate the total
total = sum(numbers)

# Step 3: Print the result
print("The sum is:", total)
```

## Output
<img width="359" height="58" alt="Screenshot 2025-10-22 211531" src="https://github.com/user-attachments/assets/525bc9b1-1358-4b4e-b5d6-80715787b0ce" />

## Result
successfully  Python program that calculates the **sum of all elements** in a list. 


# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```py
import re

# Step 2: Initialize an empty list
l1 = []

# Step 3: Define the list of words
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

# Step 4: Iterate and filter
for i in items:
    if not re.search(r"e", i):
        l1.append(i)

# Step 5: Print the filtered list
print("Words without 'e':", l1)
```
## Output
<img width="489" height="51" alt="Screenshot 2025-10-22 211852" src="https://github.com/user-attachments/assets/8c347c34-4a32-4e23-94f5-e3abc473b723" />

## Result
successfully Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.


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


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```py
# Step 1: Define a tuple
x = ('a', 'b', 'n', 5, 8, 10)

# Step 2: Check if 'n' is in the tuple
print("'n' in tuple:", 'n' in x)

# Step 3: Check if 8 is in the tuple
print("8 in tuple:", 8 in x)
```

## Output
<img width="330" height="116" alt="Screenshot 2025-10-22 212816" src="https://github.com/user-attachments/assets/550bdaef-e3a8-4047-b5b1-4c12b47f2ffb" />

## Result
successfully Python program that checks if the element `'n'` and the element `8` exist within a given tuple.
