<h1>🔹 19 Dictionary Assessments in Python 🐍</h1>

<p>This document provides 19 dictionary assessments in Python, ranging from easy to hard, including their solutions and expected results.</p>

<h2>🔹 Easy Assessments</h2>

<h3>🔹 1. Create a Dictionary</h3>

<p>Write a function that creates a dictionary from two lists: one for keys and one for values.</p>

<p>```python
def create_dict(keys, values):
    return dict(zip(keys, values))</p>

<h1>🔹 Test</h1>

<p>print(create_dict(['a', 'b', 'c'], [1, 2, 3]))  # Output: {'a': 1, 'b': 2, 'c': 3}
```</p>

<h3>🔹 2. Access Dictionary Elements</h3>

<p>Write a function to access an element by key in a dictionary.</p>

<p>```python
def access_element(d, key):
    return d.get(key, None)</p>

<h1>🔹 Test</h1>

<p>print(access<em>element({'a': 1, 'b': 2}, 'a'))  # Output: 1
print(access</em>element({'a': 1, 'b': 2}, 'c'))  # Output: None
```</p>

<h3>🔹 3. Add Element to Dictionary</h3>

<p>Write a function to add a key-value pair to a dictionary.</p>

<p>```python
def add_element(d, key, value):
    d[key] = value
    return d</p>

<h1>🔹 Test</h1>

<p>print(add_element({'a': 1, 'b': 2}, 'c', 3))  # Output: {'a': 1, 'b': 2, 'c': 3}
```</p>

<h3>🔹 4. Remove Element from Dictionary</h3>

<p>Write a function to remove a key-value pair from a dictionary.</p>

<p>```python
def remove_element(d, key):
    d.pop(key, None)
    return d</p>

<h1>🔹 Test</h1>

<p>print(remove_element({'a': 1, 'b': 2, 'c': 3}, 'b'))  # Output: {'a': 1, 'c': 3}
```</p>

<h3>🔹 5. Check Key in Dictionary</h3>

<p>Write a function to check if a key exists in a dictionary.</p>

<p>```python
def check_key(d, key):
    return key in d</p>

<h1>🔹 Test</h1>

<p>print(check<em>key({'a': 1, 'b': 2}, 'b'))  # Output: True
print(check</em>key({'a': 1, 'b': 2}, 'c'))  # Output: False
```</p>

<h2>🔹 Medium Assessments</h2>

<h3>🔹 6. Iterate Over Dictionary</h3>

<p>Write a function to iterate over a dictionary and print each key-value pair.</p>

<p>```python
def iterate_dict(d):
    for key, value in d.items():
        print(key, value)</p>

<h1>🔹 Test</h1>

<p>iterate_dict({'a': 1, 'b': 2})  # Output: "a 1", "b 2"
```</p>

<h3>🔹 7. Merge Dictionaries</h3>

<p>Write a function to merge two dictionaries.</p>

<p>```python
def merge_dicts(d1, d2):
    d1.update(d2)
    return d1</p>

<h1>🔹 Test</h1>

<p>print(merge_dicts({'a': 1, 'b': 2}, {'c': 3, 'd': 4}))  # Output: {'a': 1, 'b': 2, 'c': 3, 'd': 4}
```</p>

<h3>🔹 8. Find Max Value in Dictionary</h3>

<p>Write a function to find the key with the maximum value in a dictionary.</p>

<p>```python
def max<em>value</em>key(d):
    return max(d, key=d.get)</p>

<h1>🔹 Test</h1>

<p>print(max<em>value</em>key({'a': 1, 'b': 2, 'c': 3}))  # Output: 'c'
```</p>

<h3>🔹 9. Find Min Value in Dictionary</h3>

<p>Write a function to find the key with the minimum value in a dictionary.</p>

<p>```python
def min<em>value</em>key(d):
    return min(d, key=d.get)</p>

<h1>🔹 Test</h1>

<p>print(min<em>value</em>key({'a': 1, 'b': 2, 'c': 3}))  # Output: 'a'
```</p>

<h3>🔹 10. Dictionary Comprehension</h3>

<p>Write a function to create a dictionary using comprehension.</p>

<p>```python
def dict_comprehension(lst):
    return {x: x**2 for x in lst}</p>

<h1>🔹 Test</h1>

<p>print(dict_comprehension([1, 2, 3]))  # Output: {1: 1, 2: 4, 3: 9}
```</p>

<h2>🔹 Hard Assessments</h2>

<h3>🔹 11. Invert Dictionary</h3>

<p>Write a function to invert a dictionary (keys become values and values become keys).</p>

<p>```python
def invert_dict(d):
    return {value: key for key, value in d.items()}</p>

<h1>🔹 Test</h1>

<p>print(invert_dict({'a': 1, 'b': 2, 'c': 3}))  # Output: {1: 'a', 2: 'b', 3: 'c'}
```</p>

<h3>🔹 12. Find Common Keys</h3>

<p>Write a function to find common keys between two dictionaries.</p>

<p>```python
def common_keys(d1, d2):
    return set(d1.keys()) &amp; set(d2.keys())</p>

<h1>🔹 Test</h1>

<p>print(common_keys({'a': 1, 'b': 2}, {'b': 3, 'c': 4}))  # Output: {'b'}
```</p>

<h3>🔹 13. Group by Key Prefix</h3>

<p>Write a function to group dictionary keys by their prefix.</p>

<p>```python
from collections import defaultdict</p>

<p>def group<em>by</em>prefix(d):
    grouped<em>dict = defaultdict(list)
    for key in d:
        prefix = key[0]
        grouped</em>dict[prefix].append((key, d[key]))
    return dict(grouped_dict)</p>

<h1>🔹 Test</h1>

<p>print(group<em>by</em>prefix({'apple': 1, 'banana': 2, 'apricot': 3}))  </p>

<h1>🔹 Output: {'a': [('apple', 1), ('apricot', 3)], 'b': [('banana', 2)]}</h1>

<p>```</p>

<h3>🔹 14. Filter Dictionary by Value</h3>

<p>Write a function to filter dictionary items by value, keeping only those with values greater than a given threshold.</p>

<p>```python
def filter<em>by</em>value(d, threshold):
    return {key: value for key, value in d.items() if value &gt; threshold}</p>

<h1>🔹 Test</h1>

<p>print(filter<em>by</em>value({'a': 1, 'b': 2, 'c': 3}, 1))  # Output: {'b': 2, 'c': 3}
```</p>

<h3>🔹 15. Sum of Dictionary Values</h3>

<p>Write a function to calculate the sum of all values in a dictionary.</p>

<p>```python
def sum_values(d):
    return sum(d.values())</p>

<h1>🔹 Test</h1>

<p>print(sum_values({'a': 1, 'b': 2, 'c': 3}))  # Output: 6
```</p>

<h3>🔹 16. Nested Dictionary Comprehension</h3>

<p>Write a function to create a nested dictionary using comprehension.</p>

<p>```python
def nested<em>dict</em>comprehension(lst):
    return {x: {y: y**2 for y in range(x)} for x in lst}</p>

<h1>🔹 Test</h1>

<p>print(nested<em>dict</em>comprehension([1, 2, 3]))  </p>

<h1>🔹 Output: {1: {0: 0}, 2: {0: 0, 1: 1}, 3: {0: 0, 1: 1, 2: 4}}</h1>

<p>```</p>

<h3>🔹 17. Most Frequent Value</h3>

<p>Write a function to find the most frequent value in a dictionary.</p>

<p>```python
from collections import Counter</p>

<p>def most<em>frequent</em>value(d):
    return Counter(d.values()).most_common(1)[0][0]</p>

<h1>🔹 Test</h1>

<p>print(most<em>frequent</em>value({'a': 1, 'b': 2, 'c': 2}))  # Output: 2
```</p>

<h3>🔹 18. Merge Dictionaries with Sum</h3>

<p>Write a function to merge two dictionaries, summing values of common keys.</p>

<p>```python
def merge<em>with</em>sum(d1, d2):
    result = Counter(d1) + Counter(d2)
    return dict(result)</p>

<h1>🔹 Test</h1>

<p>print(merge<em>with</em>sum({'a': 1, 'b': 2}, {'b': 3, 'c': 4}))  # Output: {'a': 1, 'b': 5, 'c': 4}
```</p>

<h3>🔹 19. Convert List of Tuples to Dictionary</h3>

<p>Write a function to convert a list of tuples into a dictionary.</p>

<p>```python
def tuples<em>to</em>dict(lst):
    return dict(lst)</p>

<h1>🔹 Test</h1>

<p>print(tuples<em>to</em>dict([('a', 1), ('b', 2), ('c', 3)]))  # Output: {'a': 1, 'b': 2, 'c': 3}
```</p>

<h3>🔹 📢 Stay Updated</h3>

<p>Be sure to ⭐ this repository to stay updated with new examples and enhancements!</p>

<h3>🔹 📄 License</h3>

<p>🔐 This project is protected under the <a href="https://mit-license.org/">MIT License</a>.</p>

<h3>🔹 Contact 📧</h3>

<p>Panagiotis Moschos - pan.moschos86@gmail.com</p>

<p>🔗 <em>Note: This is a Python script and requires a Python interpreter to run.</em></p>

<hr />

<h1 align=center>Happy Coding 👨‍💻 </h1>

<p align="center">
  Made with ❤️ by Panagiotis Moschos (https://github.com/pmoschos)
</p>