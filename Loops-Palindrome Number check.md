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
<img width="589" height="256" alt="image" src="https://github.com/user-attachments/assets/d1142970-88e7-4632-869f-878ddbcd0226" />

## Output
<img width="869" height="187" alt="image" src="https://github.com/user-attachments/assets/c4fe78e7-3048-4324-9afd-afa61bf238d2" />

## Result
Thus a Python program that checks whether a given number is a **palindrome** using loops is created.
