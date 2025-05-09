
# Type Casting in Python 🐍

Type casting, also known as type conversion, is the process of converting one data type to another. Python provides several built-in functions for type casting.

## Implicit Type Casting

Python automatically converts one data type to another without any user involvement. This type of conversion is called implicit type casting.

```python
# Implicit type casting
x = 10
y = 3.14
result = x + y  # x is automatically converted to float
print(result)   # Output: 13.14
```

## Explicit Type Casting

Explicit type casting is when the programmer manually converts one data type to another using built-in functions.

### 1. 🔢 **int()**
Converts a value to an integer.

```python
# Convert float to int
flt = 3.14
num = int(flt)  # Output: 3

# Convert string to int
s = "123"
num = int(s)    # Output: 123
```

### 2. 💧 **float()**
Converts a value to a floating-point number.

```python
# Convert int to float
num = 10
flt = float(num)  # Output: 10.0

# Convert string to float
s = "123.45"
flt = float(s)    # Output: 123.45
```

### 3. 📜 **str()**
Converts a value to a string.

```python
# Convert int to string
num = 10
s = str(num)  # Output: "10"

# Convert float to string
flt = 3.14
s = str(flt)  # Output: "3.14"
```

### 4. 📋 **list()**
Converts a value to a list.

```python
# Convert string to list
s = "Hello"
lst = list(s)  # Output: ['H', 'e', 'l', 'l', 'o']

# Convert tuple to list
t = (1, 2, 3)
lst = list(t)  # Output: [1, 2, 3]
```

### 5. 🔗 **tuple()**
Converts a value to a tuple.

```python
# Convert list to tuple
lst = [1, 2, 3]
t = tuple(lst)  # Output: (1, 2, 3)

# Convert string to tuple
s = "Hello"
t = tuple(s)  # Output: ('H', 'e', 'l', 'l', 'o')
```

### 6. 🔄 **set()**
Converts a value to a set.

```python
# Convert list to set
lst = [1, 2, 3, 1, 2]
s = set(lst)  # Output: {1, 2, 3}

# Convert tuple to set
t = (1, 2, 3, 1, 2)
s = set(t)  # Output: {1, 2, 3}
```

### 7. 📑 **dict()**
Converts a sequence of key-value pairs to a dictionary.

```python
# Convert list of tuples to dictionary
lst = [('a', 1), ('b', 2)]
d = dict(lst)  # Output: {'a': 1, 'b': 2}

# Convert tuple of tuples to dictionary
t = (('a', 1), ('b', 2))
d = dict(t)  # Output: {'a': 1, 'b': 2}
```

## Type Casting Examples

Here are some examples of type casting in Python:

```python
# Example 1: Convert string to integer
s = "100"
num = int(s)
print(num)  # Output: 100

# Example 2: Convert integer to float
num = 50
flt = float(num)
print(flt)  # Output: 50.0

# Example 3: Convert list to set
lst = [1, 2, 3, 1, 2]
s = set(lst)
print(s)  # Output: {1, 2, 3}
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
