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
string = "google"
reversed_string = string[::-1]

if string == reversed_string:
    print(f'"{string}" is a palindrome')
else:
    print(f'"{string}" is not a palindrome')
    
## Output
Input (String)	Explanation	Output (Program prints)
"google"	Reverse and compare	"google" is not a palindrome
"level"	Reverse and compare	"level" is a palindrome
"radar"	Reverse and compare	"radar" is a palindrome

## Result
The program correctly checks whether a string is a palindrome without using built-in palindrome checking functions.
