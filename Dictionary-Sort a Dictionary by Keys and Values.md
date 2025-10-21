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

## 🧪Program
```
a={2:56,1:2,5:12,4:24,6:18,3:323}
sorted_keys=dict(sorted(a.items()))
sorted_values=dict(sorted(a.items(), key=lambda item: item[1]))
print("original:",a)
print("Keys in alphabetical order:",sorted_keys)
print("Values in alphabetical order:",sorted_values)

```

## Sample Output

<img width="1275" height="203" alt="image" src="https://github.com/user-attachments/assets/be3db517-a161-4a7c-b621-a4e183c304b0" />


## Result
The program is executed.

