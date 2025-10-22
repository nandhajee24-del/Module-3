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

