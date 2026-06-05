# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

Add code here

```
numbers = [10, 20, 30, 40, 50]
total = sum(numbers)
print(total)

```
## Output
<img width="1418" height="440" alt="image" src="https://github.com/user-attachments/assets/9d312f24-f06b-4b72-a677-bd51280138d4" />

## Result
Thus To write a Python program that calculates the sum of all elements in a list. Hence the code has been executed successfully.


---------------------------------------------------------------------------------------------

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
Add code here
```
import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i): 
        l1.append(i)

print(l1)
```
## Output
<img width="1462" height="557" alt="image" src="https://github.com/user-attachments/assets/74977e41-285d-42f3-a4a4-7ce16cea6ce1" />

## Result
Thus To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex). Hence the code has been executed successfully

-------------------------------------------------------------------------------------------------

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
Add Code Here
```
def remove(s):
    n = int(input("Enter the index to remove: ")) 
    a = "" 
    for i in range(len(s)): 
        if i != n: 
            a += s[i] 
    return a

input_string = input("Enter a string: ") 
result = remove(input_string) 
print("Modified string:", result)
```
## Output
<img width="1562" height="506" alt="image" src="https://github.com/user-attachments/assets/0a47af2b-7f0b-44a9-b9db-ffd6712c98dc" />

## Result
Thus To write a Python program that accepts a string and removes the character at a specified index. Hence the code has been executed successfully.


-----------------------------------------------------------------------------------------------

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
```
s = "google"
reversed_s = s[::-1]

if s == reversed_s:
    print("The string is a palindrome.") 
else: 
    print("The string is not a palindrome.")
```
<img width="332" height="137" alt="Screenshot 2026-06-05 201733" src="https://github.com/user-attachments/assets/4e8cc1f1-6e9f-4a2a-bfc9-86a6822e357d" />

## Output
<img width="248" height="76" alt="Screenshot 2026-06-05 201737" src="https://github.com/user-attachments/assets/b91b99f0-f980-47dc-827d-4621d6f1712a" />

## Result
Thus To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions. Hence the code has been executed successfully.

--------------------------------------------------------------------------------------------------------

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'b', 'n', 5, 8, 3)

print('n' in x)
 print(8 in x)
```

<img width="277" height="101" alt="Screenshot 2026-06-05 201855" src="https://github.com/user-attachments/assets/f710b8e9-79e9-4821-9ff2-533e4e6c999d" />

## Output

<img width="205" height="92" alt="Screenshot 2026-06-05 201901" src="https://github.com/user-attachments/assets/068ca327-56eb-467e-a846-17780fa45233" />


## Result
Thus To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple. Hence the code has been executed successfully.

