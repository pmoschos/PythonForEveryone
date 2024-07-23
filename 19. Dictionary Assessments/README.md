
# 📚 Python Dictionary Assessments

## Easy

### 1. 🌟 Dictionary Creation
**Task**: Create a dictionary named `student` with keys `name`, `age`, and `grade`. Set the values to `"John Doe"`, `21`, and `"A"`, respectively.

```python
# Your code here
student = {"name": "John Doe", "age": 21, "grade": "A"}
print(student)
```

### 2. 🌟 Accessing Values
**Task**: Print the value associated with the key `name` in the `student` dictionary.

```python
# Your code here
print(student["name"])
```

### 3. 🌟 Updating Values
**Task**: Update the `age` value to `22` in the `student` dictionary.

```python
# Your code here
student["age"] = 22
print(student)
```

### 4. 🌟 Adding Key-Value Pairs
**Task**: Add a new key `major` with the value `"Computer Science"` to the `student` dictionary.

```python
# Your code here
student["major"] = "Computer Science"
print(student)
```

### 5. 🌟 Deleting Key-Value Pairs
**Task**: Remove the `grade` key-value pair from the `student` dictionary.

```python
# Your code here
del student["grade"]
print(student)
```

## Medium

### 6. 🔄 Iterating Through a Dictionary
**Task**: Iterate through the `student` dictionary and print each key and value.

```python
# Your code here
for key, value in student.items():
    print(f"{key}: {value}")
```

### 7. 🔄 Dictionary Comprehension
**Task**: Create a dictionary named `squares` with numbers from 1 to 5 as keys and their squares as values using dictionary comprehension.

```python
# Your code here
squares = {x: x**2 for x in range(1, 6)}
print(squares)
```

### 8. 🔄 Nested Dictionaries
**Task**: Create a dictionary `classroom` with two students having their own dictionaries with keys `name` and `age`.

```python
# Your code here
classroom = {
    "student1": {"name": "John", "age": 22},
    "student2": {"name": "Jane", "age": 23}
}
print(classroom)
```

### 9. 🔄 Dictionary Methods
**Task**: Use the `get` method to retrieve the value of `major` from the `student` dictionary. If the key does not exist, return `"Not Specified"`.

```python
# Your code here
major = student.get("major", "Not Specified")
print(major)
```

### 10. 🔄 Merging Dictionaries
**Task**: Merge two dictionaries: `dict1 = {'a': 1, 'b': 2}` and `dict2 = {'b': 3, 'c': 4}`.

```python
# Your code here
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}
merged_dict = {**dict1, **dict2}
print(merged_dict)
```

## Hard

### 11. 🚀 Complex Nested Dictionaries
**Task**: Create a complex nested dictionary representing a `company` with departments, each containing a list of employees. Each employee is represented by a dictionary with `name` and `position`.

```python
# Your code here
company = {
    "Engineering": [
        {"name": "Alice", "position": "Software Engineer"},
        {"name": "Bob", "position": "DevOps Engineer"}
    ],
    "HR": [
        {"name": "Eve", "position": "HR Manager"},
        {"name": "Charlie", "position": "Recruiter"}
    ]
}
print(company)
```

### 12. 🚀 Dictionary from Two Lists
**Task**: Create a dictionary from two lists: `keys = ["name", "age", "grade"]` and `values = ["Alice", 23, "A"]`.

```python
# Your code here
keys = ["name", "age", "grade"]
values = ["Alice", 23, "A"]
student_dict = dict(zip(keys, values))
print(student_dict)
```

### 13. 🚀 Dictionary with Default Values
**Task**: Create a dictionary `default_dict` with default values using `defaultdict` from the `collections` module. Initialize with integer type.

```python
# Your code here
from collections import defaultdict
default_dict = defaultdict(int)
default_dict['count'] += 1
print(default_dict)
```

### 14. 🚀 Counting Elements
**Task**: Count the occurrences of each character in a string using a dictionary.

```python
# Your code here
input_string = "abracadabra"
char_count = {}
for char in input_string:
    if char in char_count:
        char_count[char] += 1
    else:
        char_count[char] = 1
print(char_count)
```

### 15. 🚀 Dictionary Sorting
**Task**: Sort a dictionary by its keys and print the sorted dictionary.

```python
# Your code here
unsorted_dict = {'c': 3, 'a': 1, 'b': 2}
sorted_dict = dict(sorted(unsorted_dict.items()))
print(sorted_dict)
```

### 16. 🚀 Inverting a Dictionary
**Task**: Invert a dictionary so that keys become values and values become keys.

```python
# Your code here
original_dict = {'a': 1, 'b': 2, 'c': 3}
inverted_dict = {value: key for key, value in original_dict.items()}
print(inverted_dict)
```

### 17. 🚀 Dictionary of Dictionaries
**Task**: Create a dictionary of dictionaries to store student information, where each student ID maps to their respective information dictionary.

```python
# Your code here
students = {
    101: {"name": "John", "age": 22, "grade": "A"},
    102: {"name": "Jane", "age": 23, "grade": "B"},
    103: {"name": "Doe", "age": 24, "grade": "C"}
}
print(students)
```

### 18. 🚀 Finding Key with Maximum Value
**Task**: Find the key with the maximum value in a dictionary.

```python
# Your code here
scores = {"Alice": 90, "Bob": 85, "Charlie": 95}
max_key = max(scores, key=scores.get)
print(max_key)
```

### 19. 🚀 Recursive Dictionary Traversal
**Task**: Write a recursive function to traverse and print all keys and values of a nested dictionary.

```python
# Your code here
def traverse_dict(d, parent_key=""):
    for key, value in d.items():
        new_key = f"{parent_key}.{key}" if parent_key else key
        if isinstance(value, dict):
            traverse_dict(value, new_key)
        else:
            print(f"{new_key}: {value}")

nested_dict = {
    "a": 1,
    "b": {
        "c": 2,
        "d": {
            "e": 3,
            "f": 4
        }
    }
}
traverse_dict(nested_dict)
```

## 📢 Stay Updated

Be sure to ⭐ this repository to stay updated with new examples and enhancements!

## 📄 License
🔐 This project is protected under the [MIT License](https://mit-license.org/).

## Contact 📧
Panagiotis Moschos - pan.moschos86@gmail.com

🔗 *Note: This is a Python script and requires a Python interpreter to run.*

---

<h1 align=center>Happy Coding 👨‍💻 </h1>

<p align="center">
  Made with ❤️ by Panagiotis Moschos (https://github.com/pmoschos)
</p>
