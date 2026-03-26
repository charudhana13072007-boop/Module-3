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
~~~
text = "google"

reversed_text = text[::-1]
if text == reversed_text:
    print(text, "is a palindrome")
else:
    print(text, "is not a palindrome")
~~~
## Output
google is not a palindrome

## Result
The program correctly identifies that the string "google" is not a palindrome, since its reverse "elgoog" does not match the original string.
