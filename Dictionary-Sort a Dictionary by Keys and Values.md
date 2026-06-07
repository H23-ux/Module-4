# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Progra

```python
# Define a dictionary with key-value pairs
my_dict = {'apple': 3, 'orange': 1, 'banana': 2}

# Sort by Keys
sorted_by_keys = dict(sorted(my_dict.items()))

# Sort by Values
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Display the original and sorted dictionaries
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
```
## Sample Output

<img width="568" height="237" alt="image" src="https://github.com/user-attachments/assets/ccb11d24-53a0-4f10-9e12-399db5e104e2" />

## Result
The Python program successfully sorts the dictionary both alphabetically by its keys and by its values using the sorted() function and converts the results back into dictionary format as intended.

