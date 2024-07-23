
# 17 Set Assessments in Python 🐍

This document provides 17 set assessments in Python, ranging from easy to hard, including their solutions and expected results.

## Easy Assessments

### 1. 🛠️ Create a Set
Write a function that creates a set from a list.

```python
def create_set(lst):
    return set(lst)

# Test
print(create_set([1, 2, 3, 4, 5]))  # Output: {1, 2, 3, 4, 5}
```

### 2. ➕ Add Element to Set
Write a function to add an element to a set.

```python
def add_element(s, elem):
    s.add(elem)
    return s

# Test
print(add_element({1, 2, 3}, 4))  # Output: {1, 2, 3, 4}
```

### 3. ➖ Remove Element from Set
Write a function to remove an element from a set.

```python
def remove_element(s, elem):
    s.discard(elem)
    return s

# Test
print(remove_element({1, 2, 3}, 2))  # Output: {1, 3}
```

### 4. ✅ Check Element in Set
Write a function to check if an element exists in a set.

```python
def check_element(s, elem):
    return elem in s

# Test
print(check_element({1, 2, 3}, 2))  # Output: True
```

### 5. 🔄 Set Union
Write a function to return the union of two sets.

```python
def set_union(s1, s2):
    return s1 | s2

# Test
print(set_union({1, 2, 3}, {3, 4, 5}))  # Output: {1, 2, 3, 4, 5}
```

## Medium Assessments

### 6. 🔄 Set Intersection
Write a function to return the intersection of two sets.

```python
def set_intersection(s1, s2):
    return s1 & s2

# Test
print(set_intersection({1, 2, 3}, {3, 4, 5}))  # Output: {3}
```

### 7. 🔄 Set Difference
Write a function to return the difference of two sets.

```python
def set_difference(s1, s2):
    return s1 - s2

# Test
print(set_difference({1, 2, 3}, {3, 4, 5}))  # Output: {1, 2}
```

### 8. 🔄 Set Symmetric Difference
Write a function to return the symmetric difference of two sets.

```python
def set_symmetric_difference(s1, s2):
    return s1 ^ s2

# Test
print(set_symmetric_difference({1, 2, 3}, {3, 4, 5}))  # Output: {1, 2, 4, 5}
```

### 9. 📑 Check Subset
Write a function to check if one set is a subset of another.

```python
def check_subset(s1, s2):
    return s1.issubset(s2)

# Test
print(check_subset({1, 2}, {1, 2, 3}))  # Output: True
```

### 10. 🔍 Check Superset
Write a function to check if one set is a superset of another.

```python
def check_superset(s1, s2):
    return s1.issuperset(s2)

# Test
print(check_superset({1, 2, 3}, {1, 2}))  # Output: True
```

### 11. 🔄 Convert Set to List
Write a function to convert a set to a list.

```python
def set_to_list(s):
    return list(s)

# Test
print(set_to_list({1, 2, 3}))  # Output: [1, 2, 3]
```

### 12. 🔍 Find Max Element in Set
Write a function to find the maximum element in a set.

```python
def max_element(s):
    return max(s)

# Test
print(max_element({1, 2, 3, 4, 5}))  # Output: 5
```

### 13. 🔍 Find Min Element in Set
Write a function to find the minimum element in a set.

```python
def min_element(s):
    return min(s)

# Test
print(min_element({1, 2, 3, 4, 5}))  # Output: 1
```

### 14. 🔄 Set Comprehension
Write a function that returns a set of squares of the elements in a set.

```python
def set_comprehension(s):
    return {x ** 2 for x in s}

# Test
print(set_comprehension({1, 2, 3}))  # Output: {1, 4, 9}
```

### 15. ❌ Remove Duplicates from List
Write a function to remove duplicates from a list using a set.

```python
def remove_duplicates(lst):
    return list(set(lst))

# Test
print(remove_duplicates([1, 2, 2, 3, 3, 3, 4]))  # Output: [1, 2, 3, 4]
```

### 16. 📏 Set Length
Write a function to find the length of a set.

```python
def set_length(s):
    return len(s)

# Test
print(set_length({1, 2, 3, 4, 5}))  # Output: 5
```

### 17. 🔍 Find Common Elements in Multiple Sets
Write a function to find common elements in multiple sets.

```python
def common_elements(*sets):
    return set.intersection(*sets)

# Test
print(common_elements({1, 2, 3}, {2, 3, 4}, {3, 4, 5}))  # Output: {3}
```

### 📢 Stay Updated

Be sure to ⭐ this repository to stay updated with new examples and enhancements!

### 📄 License
🔐 This project is protected under the [MIT License](https://mit-license.org/).

### Contact 📧
Panagiotis Moschos - pan.moschos86@gmail.com

🔗 *Note: This is a Python script and requires a Python interpreter to run.*

---

<h1 align=center>Happy Coding 👨‍💻 </h1>

<p align="center">
  Made with ❤️ by Panagiotis Moschos (https://github.com/pmoschos)
</p>
