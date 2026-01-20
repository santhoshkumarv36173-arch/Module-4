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
try:
   l = [1,2,3,4]
   print(l[5])
except IndexError:
   print("You're out of list range")
```

## Output
<img width="819" height="208" alt="530462567-4dd6a632-4a1d-4686-b7c8-2b12ae7cf910" src="https://github.com/user-attachments/assets/c252bfb3-46f9-4f6c-a9ab-3a731ba6fc26" />

## Result
Thus To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list is executed successfully.
