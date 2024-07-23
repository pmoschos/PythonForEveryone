
# Tuples in Python 🐍

Tuples are another commonly used data type in Python. They are immutable, ordered collections of items that can be of different types.

## Why Use Tuples? 🤔

- **Immutability**: Tuples cannot be changed after creation, which makes them useful for fixed collections of items.
- **Efficiency**: Tuples are generally more memory efficient than lists.
- **Hashable**: Tuples can be used as keys in dictionaries because they are immutable and hashable.

## 🔤 Creating Tuples

You can create a tuple by enclosing items in parentheses `()`.

```python
# Empty tuple
empty_tuple = ()

# Tuple of integers
int_tuple = (1, 2, 3, 4, 5)

# Tuple of strings
str_tuple = ("apple", "banana", "cherry")

# Mixed type tuple
mixed_tuple = (1, "hello", 3.14, True)

print(empty_tuple)
print(int_tuple)
print(str_tuple)
print(mixed_tuple)
```

## 🔍 Accessing Tuple Elements

You can access elements in a tuple by their index. Python uses zero-based indexing.

```python
fruits = ("apple", "banana", "cherry")

# Accessing the first element
print(fruits[0])  # Output: apple

# Accessing the last element
print(fruits[-1])  # Output: cherry

# Accessing a slice of the tuple
print(fruits[1:3])  # Output: ('banana', 'cherry')
```

## 🛠️ Tuple Operations

### ➕ Concatenation

You can concatenate tuples using the `+` operator.

```python
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
concatenated_tuple = tuple1 + tuple2
print(concatenated_tuple)  # Output: (1, 2, 3, 4, 5, 6)
```

### ✖️ Repetition

You can repeat a tuple using the `*` operator.

```python
tuple1 = (1, 2, 3)
repeated_tuple = tuple1 * 3
print(repeated_tuple)  # Output: (1, 2, 3, 1, 2, 3, 1, 2, 3)
```

## 💡 Practical Applications

### 🔄 Returning Multiple Values from a Function

Tuples are often used to return multiple values from a function.

```python
def get_student_info():
    name = "Alice"
    age = 20
    grade = "A"
    return (name, age, grade)

info = get_student_info()
print(info)  # Output: ('Alice', 20, 'A')
```

### 🔑 Using Tuples as Dictionary Keys

Because tuples are immutable, they can be used as keys in dictionaries.

```python
locations = {
    (40.7128, 74.0060): "New York",
    (34.0522, 118.2437): "Los Angeles",
    (37.7749, 122.4194): "San Francisco"
}

print(locations)
```

## 🔒 Immutability

Tuples are immutable, which means you cannot modify their elements after creation.

```python
fruits = ("apple", "banana", "cherry")

# Trying to modify an element will raise an error
# fruits[0] = "orange"  # TypeError: 'tuple' object does not support item assignment
```

## 📝 Tuple Methods

Tuples support only a few methods because of their immutability.

### Count

Returns the number of times a specified value occurs in a tuple.

```python
numbers = (1, 2, 3, 2, 2, 4)
count_of_twos = numbers.count(2)
print(count_of_twos)  # Output: 3
```

### Index

Returns the index of the first occurrence of a specified value.

```python
numbers = (1, 2, 3, 4, 2, 5)
index_of_two = numbers.index(2)
print(index_of_two)  # Output: 1
```

## 📜 Conclusion

Tuples are a useful data type for storing ordered, immutable collections of items. Their immutability provides data integrity and can be useful in various programming scenarios where a fixed collection of items is required. They are memory efficient and can be used as dictionary keys, making them versatile in different applications.

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