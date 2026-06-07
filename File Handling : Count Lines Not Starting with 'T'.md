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
## 🧾 Program

```python
count = 0
with open("story.txt", "r") as file:
    for line in file:
        if not line.startswith("T"):
            count += 1

print("Total lines not starting with 'T':", count)
```

## Output

<img width="476" height="236" alt="image" src="https://github.com/user-attachments/assets/30b8a880-865e-4530-9416-9ad7ad552fd6" />

## Result
The Python program successfully opens the file story.txt, iterates through each line to verify if it does not begin with the character 'T', and accurately prints the total count of those lines.
