
# Simple Printing Patterns in Python 🐍

Printing patterns is a common exercise to understand loops and iterations in Python. Here are some simple examples of printing patterns using loops.

## 1. ⬛ Printing a Square Pattern

```python
# Example of printing a square pattern
n = 5
for i in range(n):
    for j in range(n):
        print("*", end=" ")
    print()
```

```
Output:
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
```

## 2. 🔼 Printing a Right-Angled Triangle Pattern

```python
# Example of printing a right-angled triangle pattern
n = 5
for i in range(1, n + 1):
    for j in range(i):
        print("*", end=" ")
    print()
```

```
Output:
*
* *
* * *
* * * *
* * * * *
```

## 3. 🔽 Printing an Inverted Right-Angled Triangle Pattern

```python
# Example of printing an inverted right-angled triangle pattern
n = 5
for i in range(n, 0, -1):
    for j in range(i):
        print("*", end=" ")
    print()
```

```
Output:
* * * * *
* * * *
* * *
* *
*
```

## 4. ⛰️ Printing a Pyramid Pattern

```python
# Example of printing a pyramid pattern
n = 5
for i in range(n):
    print(' ' * (n - i - 1) + '* ' * (i + 1))
```

```
Output:
    *
   * *
  * * *
 * * * *
* * * * *
```

## 5. ⛰️ Printing an Inverted Pyramid Pattern

```python
# Example of printing an inverted pyramid pattern
n = 5
for i in range(n, 0, -1):
    print(' ' * (n - i) + '* ' * i)
```

```
Output:
* * * * *
 * * * *
  * * *
   * *
    *
```

## 6. 🔷 Printing a Diamond Pattern

```python
# Example of printing a diamond pattern
n = 5
for i in range(n):
    print(' ' * (n - i - 1) + '* ' * (i + 1))
for i in range(n-1, 0, -1):
    print(' ' * (n - i) + '* ' * i)
```

```
Output:
    *
   * *
  * * *
 * * * *
* * * * *
 * * * *
  * * *
   * *
    *
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
