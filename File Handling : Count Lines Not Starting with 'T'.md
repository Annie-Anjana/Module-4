# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
Add code here
```
def count_lines_not_starting_with_T(filename):
    count = 0
    try:
        with open(filename, 'r') as file:
            for line in file:
                if line and line[0] != 'T':
                    count += 1
        print("Number of lines not starting with 'T':", count)
    except FileNotFoundError:
        print(f"The file '{filename}' was not found.")
count_lines_not_starting_with_T('story.txt')
```
## Output
![Screenshot 2025-04-30 205604](https://github.com/user-attachments/assets/59486158-9245-4cd0-85f9-0bb38a31ddd6)
## Result
The code executed successfully.
