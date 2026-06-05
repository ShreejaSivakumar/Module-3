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
```
import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i): 
        l1.append(i)

print(l1)
```
<img width="593" height="302" alt="Screenshot 2026-06-05 201518" src="https://github.com/user-attachments/assets/67d48c2e-9110-49db-b93a-76d2530d7577" />


## Output
<img width="373" height="105" alt="Screenshot 2026-06-05 201523" src="https://github.com/user-attachments/assets/1c84075a-5603-43cb-940f-4ef594e3cf40" />

## Result
Thus To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex). Hence the code has been executed successfully.
