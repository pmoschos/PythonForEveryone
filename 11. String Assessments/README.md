
# 11 String Assessments in Python 🐍

This document provides 21 string assessments in Python, ranging from easy to hard, including their solutions and expected results.

## Easy Assessments

### 1. 🔄 Reverse a String
Write a function that reverses a given string.

```python
def reverse_string(s):
    return s[::-1]

# Test
print(reverse_string("hello"))  # Output: "olleh"
```

### 2. 🔍 Check Palindrome
Write a function to check if a given string is a palindrome.

```python
def is_palindrome(s):
    return s == s[::-1]

# Test
print(is_palindrome("radar"))  # Output: True
print(is_palindrome("hello"))  # Output: False
```

### 3. 🅰️ Count Vowels
Write a function that counts the number of vowels in a given string.

```python
def count_vowels(s):
    vowels = "aeiouAEIOU"
    return sum(1 for char in s if char in vowels)

# Test
print(count_vowels("hello"))  # Output: 2
```

### 4. 🚫 Remove Whitespace
Write a function to remove all whitespace from a string.

```python
def remove_whitespace(s):
    return s.replace(" ", "")

# Test
print(remove_whitespace("hello world"))  # Output: "helloworld"
```

### 5. 📏 Find the Length of a String
Write a function to find the length of a string.

```python
def string_length(s):
    return len(s)

# Test
print(string_length("hello"))  # Output: 5
```

## Medium Assessments

### 6. 🔄 Replace Substring
Write a function to replace all occurrences of a substring with another substring.

```python
def replace_substring(s, old, new):
    return s.replace(old, new)

# Test
print(replace_substring("hello world", "world", "Python"))  # Output: "hello Python"
```

### 7. 🔍 Find Substring
Write a function to find the index of the first occurrence of a substring.

```python
def find_substring(s, sub):
    return s.find(sub)

# Test
print(find_substring("hello world", "world"))  # Output: 6
```

### 8. 📝 Count Words
Write a function to count the number of words in a string.

```python
def count_words(s):
    return len(s.split())

# Test
print(count_words("hello world"))  # Output: 2
```

### 9. 🔠 Convert to Uppercase
Write a function to convert a string to uppercase.

```python
def to_uppercase(s):
    return s.upper()

# Test
print(to_uppercase("hello"))  # Output: "HELLO"
```

### 10. 🔡 Convert to Lowercase
Write a function to convert a string to lowercase.

```python
def to_lowercase(s):
    return s.lower()

# Test
print(to_lowercase("HELLO"))  # Output: "hello"
```

### 11. 🔄 Swap Case
Write a function to swap the case of each character in a string.

```python
def swap_case(s):
    return s.swapcase()

# Test
print(swap_case("Hello World"))  # Output: "hELLO wORLD"
```

## Hard Assessments

### 12. 📊 Count Character Frequency
Write a function to count the frequency of each character in a string.

```python
def character_frequency(s):
    freq = {}
    for char in s:
        if char in freq:
            freq[char] += 1
        else:
            freq[char] = 1
    return freq

# Test
print(character_frequency("hello"))  # Output: {'h': 1, 'e': 1, 'l': 2, 'o': 1}
```

### 13. 🔀 Remove Duplicates
Write a function to remove duplicate characters from a string.

```python
def remove_duplicates(s):
    return ''.join(sorted(set(s), key=s.index))

# Test
print(remove_duplicates("hello"))  # Output: "helo"
```

### 14. 🔢 Convert String to Integer
Write a function to convert a string to an integer.

```python
def string_to_integer(s):
    try:
        return int(s)
    except ValueError:
        return None

# Test
print(string_to_integer("123"))  # Output: 123
print(string_to_integer("hello"))  # Output: None
```

### 15. 🔤 Convert Integer to String
Write a function to convert an integer to a string.

```python
def integer_to_string(n):
    return str(n)

# Test
print(integer_to_string(123))  # Output: "123"
```

### 16. 🔄 Reverse Words
Write a function to reverse the order of words in a string.

```python
def reverse_words(s):
    return ' '.join(s.split()[::-1])

# Test
print(reverse_words("hello world"))  # Output: "world hello"
```

### 17. 🏆 Most Frequent Character
Write a function to find the most frequent character in a string.

```python
def most_frequent_character(s):
    return max(s, key=s.count)

# Test
print(most_frequent_character("banana"))  # Output: "a"
```

### 18. 🔤 Check if a String is a Valid Identifier
Write a function to check if a string is a valid identifier in Python.

```python
def is_valid_identifier(s):
    return s.isidentifier()

# Test
print(is_valid_identifier("variable"))  # Output: True
print(is_valid_identifier("123variable"))  # Output: False
```

### 19. 🐍 Convert CamelCase to Snake_case
Write a function to convert a CamelCase string to snake_case.

```python
import re

def camel_to_snake(s):
    return re.sub(r'(?<!^)(?=[A-Z])', '_', s).lower()

# Test
print(camel_to_snake("CamelCaseString"))  # Output: "camel_case_string"
```

### 20. 🔄 Find All Permutations of a String
Write a function to find all permutations of a given string.

```python
from itertools import permutations

def all_permutations(s):
    return [''.join(p) for p in permutations(s)]

# Test
print(all_permutations("abc"))  # Output: ['abc', 'acb', 'bac', 'bca', 'cab', 'cba']
```

### 21. 🔠 Check if a String is a Pangram
Write a function to check if a string is a pangram (contains all the letters of the alphabet at least once).

```python
import string

def is_pangram(s):
    return set(string.ascii_lowercase) <= set(s.lower())

# Test
print(is_pangram("The quick brown fox jumps over the lazy dog"))  # Output: True
print(is_pangram("Hello World"))  # Output: False
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
