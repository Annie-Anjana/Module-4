## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
Add code here
```
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}
def merge():
    merged_dict = {**dict1, **dict2}  # dict2 values will overwrite dict1 if keys overlap
    return merged_dict
result = merge()
print("Merged dictionary:", result)
```
## Output

![Screenshot 2025-04-30 204151](https://github.com/user-attachments/assets/8f00b04c-e85a-4595-a3aa-835ea83f3a45)
## Result
The code executed successfully.
