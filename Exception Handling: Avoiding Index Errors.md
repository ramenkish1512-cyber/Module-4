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
```
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
```

## Output
<img width="774" height="192" alt="Screenshot 2026-06-07 203604" src="https://github.com/user-attachments/assets/88cde5f4-1298-4635-8be4-490be2db5bc4" />

## Result
Thus the program was successfully executed.
