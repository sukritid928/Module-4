## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```

## Output
<img width="966" height="290" alt="530399041-1a79270d-003e-4a94-bb08-d0f93f0e0cc9" src="https://github.com/user-attachments/assets/2f30aaea-b702-4a9e-9332-1410ba754e41" />


## Result
Thus the program executed successfully.
