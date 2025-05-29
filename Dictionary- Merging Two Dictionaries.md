## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
~~~
## Output
![438328698-75f6d01f-afb0-4189-b9ba-6497464fa600](https://github.com/user-attachments/assets/f52694e1-8d21-4cbd-af08-b8cd62bc454c)
![438328804-b2feb9ac-407d-4ee5-a669-0c2b55bb7173](https://github.com/user-attachments/assets/1897de83-940b-4aa5-aa15-8e9cce3ad8be)


## Result
Thus the program executed successfully.
