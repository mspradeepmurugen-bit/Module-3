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
```a="google"
rev=a[::-1]
if a==rev:
    print("the string is a palindrome")
else:
    print("the string is not a palindrome")
```

## Output
<img width="1019" height="165" alt="Screenshot 2025-12-28 142146" src="https://github.com/user-attachments/assets/039ed3e9-155a-473d-bae0-81eea12baa88" />

## Result
thus the python program is executed sucessfully
