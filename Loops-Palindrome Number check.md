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
num=int(input())
temp=num
a = len(str(num))
rev=0
for i in range(a):
    d = temp%10
    rev = rev*10+d
    temp//=10
    
if num==rev:
    print(f"The given number {num} is a Palindrome")
else:
    print(f"The given number {num} is not a palindrome")
```
## Output
<img width="1050" height="233" alt="Screenshot 2025-10-20 204028" src="https://github.com/user-attachments/assets/12260a27-31fb-454c-b077-0f204c3433e1" />

## Result
Thus, the python program to check whether the given number is palindrome or not is created successfully.
