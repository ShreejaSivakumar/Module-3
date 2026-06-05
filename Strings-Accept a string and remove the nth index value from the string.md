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

<img width="346" height="203" alt="Screenshot 2026-06-05 201626" src="https://github.com/user-attachments/assets/962dd7b4-6c5b-4683-a3bc-8c2dfaa999f3" />

## Output
<img width="247" height="103" alt="Screenshot 2026-06-05 201632" src="https://github.com/user-attachments/assets/8a4f58a9-f686-4bb8-81db-64f31d47cc71" />

## Result
Thus To write a Python program that accepts a string and removes the character at a specified index. Hence the code has been executed successfully.
