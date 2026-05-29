# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```python
a = int(input("Enter a number: "))

if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```

## Output
Output 1

Enter a number: 8

EVEN

Output 2

Enter a number: 7

ODD

## Result
Thus, the Python program to check whether a given number is even or odd using if...else statements was successfully executed.
