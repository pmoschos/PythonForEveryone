
# 15 Tuple Assessments in Python 🐍

This document provides 15 tuple assessments in Python, ranging from easy to hard, including their solutions and expected results.

## Easy Assessments

### 1. 🔍 Access Tuple Elements
Write a function that accesses the elements of a tuple.

```python
def access_elements(tpl):
    return tpl[0], tpl[-1]

# Test
print(access_elements((1, 2, 3, 4, 5)))  # Output: (1, 5)
```

### 2. ➕ Concatenate Tuples
Write a function to concatenate two tuples.

```python
def concatenate_tuples(tpl1, tpl2):
    return tpl1 + tpl2

# Test
print(concatenate_tuples((1, 2), (3, 4)))  # Output: (1, 2, 3, 4)
```

### 3. 📏 Find Length of Tuple
Write a function to find the length of a tuple.

```python
def tuple_length(tpl):
    return len(tpl)

# Test
print(tuple_length((1, 2, 3, 4, 5)))  # Output: 5
```

### 4. ✅ Check Element in Tuple
Write a function to check if an element exists in a tuple.

```python
def check_element(tpl, elem):
    return elem in tpl

# Test
print(check_element((1, 2, 3, 4, 5), 3))  # Output: True
```

### 5. 🔄 Convert List to Tuple
Write a function to convert a list to a tuple.

```python
def list_to_tuple(lst):
    return tuple(lst)

# Test
print(list_to_tuple([1, 2, 3, 4, 5]))  # Output: (1, 2, 3, 4, 5)
```

## Medium Assessments

### 6. 🔓 Unpack Tuple
Write a function to unpack the elements of a tuple into variables.

```python
def unpack_tuple(tpl):
    a, b, c = tpl
    return a, b, c

# Test
print(unpack_tuple((1, 2, 3)))  # Output: (1, 2, 3)
```

### 7. 🔍 Find Index of Element
Write a function to find the index of an element in a tuple.

```python
def index_of_element(tpl, elem):
    return tpl.index(elem)

# Test
print(index_of_element((1, 2, 3, 4, 5), 3))  # Output: 2
```

### 8. 🔢 Count Element in Tuple
Write a function to count the number of times an element appears in a tuple.

```python
def count_element(tpl, elem):
    return tpl.count(elem)

# Test
print(count_element((1, 2, 2, 3, 4, 4, 5), 2))  # Output: 2
```

### 9. 🔄 Convert Tuple to List
Write a function to convert a tuple to a list.

```python
def tuple_to_list(tpl):
    return list(tpl)

# Test
print(tuple_to_list((1, 2, 3, 4, 5)))  # Output: [1, 2, 3, 4, 5]
```

### 10. ✖️ Multiply Elements in Tuple
Write a function to multiply each element in a tuple by a given number.

```python
def multiply_elements(tpl, num):
    return tuple(x * num for x in tpl)

# Test
print(multiply_elements((1, 2, 3), 2))  # Output: (2, 4, 6)
```

## Hard Assessments

### 11. 🔍 Find Min and Max
Write a function to find the minimum and maximum elements in a tuple.

```python
def min_max_elements(tpl):
    return min(tpl), max(tpl)

# Test
print(min_max_elements((1, 2, 3, 4, 5)))  # Output: (1, 5)
```

### 12. 🔄 Convert Tuple of Tuples to a Single Tuple
Write a function to convert a tuple of tuples into a single tuple.

```python
def flatten_tuple(tpl):
    return tuple(item for subtuple in tpl for item in subtuple)

# Test
print(flatten_tuple(((1, 2), (3, 4), (5, 6))))  # Output: (1, 2, 3, 4, 5, 6)
```

### 13. 🔄 Sort Tuple
Write a function to sort the elements of a tuple.

```python
def sort_tuple(tpl):
    return tuple(sorted(tpl))

# Test
print(sort_tuple((3, 1, 2, 5, 4)))  # Output: (1, 2, 3, 4, 5)
```

### 14. 🔄 Find Duplicates in Tuple
Write a function to find duplicate elements in a tuple.

```python
def find_duplicates(tpl):
    return tuple(x for x in set(tpl) if tpl.count(x) > 1)

# Test
print(find_duplicates((1, 2, 2, 3, 3, 3, 4)))  # Output: (2, 3)
```

### 15. 🔗 Merge Tuple Elements into String
Write a function to merge the elements of a tuple into a single string with a separator.

```python
def merge_with_separator(tpl, sep):
    return sep.join(map(str, tpl))

# Test
print(merge_with_separator((1, 2, 3), '-'))  # Output: "1-2-3"
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
