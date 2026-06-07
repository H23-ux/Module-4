## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

## 💻 Program

```python
# Step 1: Define two dictionaries with some key-value pairs
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

# Step 2: Define a function that merges them using the ** unpacking operator
def merge(d1, d2):
    # Unpacking both dictionaries into a new one
    # dict2 will overwrite duplicate keys from dict1 (like 'b')
    merged_dict = {**d1, **d2}
    return merged_dict

# Step 3: Call the function and print the result
result_dict = merge(dict1, dict2)
print("Dictionary 1:", dict1)
print("Dictionary 2:", dict2)
print("Merged Dictionary:", result_dict)
```
## Output

<img width="509" height="255" alt="image" src="https://github.com/user-attachments/assets/5d5b74ca-3bf1-417e-9aa0-a4bc5f427e18" />

## Result
The Python program successfully merged the two dictionaries using the dictionary unpacking operator (). As specified in the algorithm, the duplicate key 'b' from dict1 was cleanly overwritten by the value from dict2.
