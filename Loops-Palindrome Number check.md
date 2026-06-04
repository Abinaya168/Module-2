## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=input()
a=num[::-1]
if a==num:
    print("pallindrome")
else:
    print("not pallindrome")

```
## Output
<img width="1121" height="280" alt="image" src="https://github.com/user-attachments/assets/2e86c4bc-cafe-41df-865a-0e14c6974a8e" />

## Result
