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
Add Code here
d = {'b': 'banana', 'a': 'apple', 'd': 'dog', 'c': 'cat'}

print("Original dictionary:", d)

# Sort by keys
sort_keys = dict(sorted(d.items()))
print("Sorted by keys:", sort_keys)

# Sort by values
sort_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by values:", sort_values)
## Sample Output
Original dictionary: {'b': 'banana', 'a': 'apple', 'd': 'dog', 'c': 'cat'}
Sorted by keys: {'a': 'apple', 'b': 'banana', 'c': 'cat', 'd': 'dog'}
Sorted by values: {'a': 'apple', 'b': 'banana', 'c': 'cat', 'd': 'dog'}
## Result
Thus, the Python program to sort a dictionary alphabetically by keys and values was executed successfully.
