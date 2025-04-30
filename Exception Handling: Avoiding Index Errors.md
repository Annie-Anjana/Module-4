# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
Add code here
```
list1 = [10, 20, 30]
try:
    value = list1[5]
    print("Accessed value:", value)
except IndexError:
    print("You're out of list range")
```
## Output
![Screenshot 2025-04-30 205041](https://github.com/user-attachments/assets/dd4bbc89-901d-4644-a237-180b3121f268)
## Result
The code executed successfully.
