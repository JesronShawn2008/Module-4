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
dic1 = eval(input())
dic2 = eval(input())
rdict={}
for key,value in dic2.items():
    rdict[key] = value
for key,value in dic1.items():
    rdict[key] = value
print(rdict)
```
## Output
<img width="1308" height="210" alt="image" src="https://github.com/user-attachments/assets/4ff866ba-4ad1-4476-ab00-e913139b1cba" />

## Result
Thus we were successfully able to write a Python program that merges **two dictionaries** and combines their key-value pairs.
