
# Escape Characters in Python 🐍

Escape characters are used in strings to insert characters that are illegal in a string. For example, to include double quotes inside a string, you can use the escape character `\`.

## Common Escape Characters

### 1. ⏎ **Newline (`\n`)**
Inserts a new line in the text at the specified point.

```python
text = "Hello,\nWorld!"
print(text)
# Output:
# Hello,
# World!
```

### 2. 🔙 **Backslash (`\\`)**
Inserts a backslash character in the text.

```python
text = "This is a backslash: \\"
print(text)
# Output: This is a backslash: \\
```

### 3. 📝 **Single Quote (`\'`)**
Inserts a single quote character in the text.

```python
text = 'It\'s a beautiful day!'
print(text)
# Output: It\'s a beautiful day!
```

### 4. 💬 **Double Quote (`\"`)**
Inserts a double quote character in the text.

```python
text = "He said, \"Hello, World!\""
print(text)
# Output: He said, "Hello, World!"
```

### 5. ↹ **Tab (`\t`)**
Inserts a tab space in the text.

```python
text = "Hello,\tWorld!"
print(text)
# Output: Hello,   World!
```

### 6. ⌫ **Backspace (`\b`)**
Inserts a backspace character in the text.

```python
text = "Hello, \bWorld!"
print(text)
# Output: Hello,World!
```

### 7. ↩️ **Carriage Return (`\r`)**
Inserts a carriage return in the text.

```python
text = "Hello,\rWorld!"
print(text)
# Output: World!
```

### 8. 📃 **Form Feed (`\f`)**
Inserts a form feed in the text.

```python
text = "Hello,\fWorld!"
print(text)
# Output: Hello,World!
```

### 9. 🐙 **Octal Value (`\ooo`)**
Inserts a character based on its octal value.

```python
text = "\110\145\154\154\157"
print(text)
# Output: Hello
```

### 10. 🔢 **Hex Value (`\xhh`)**
Inserts a character based on its hex value.

```python
text = "\x48\x65\x6c\x6c\x6f"
print(text)
# Output: Hello
```

## Raw Strings

In raw strings, escape characters are not processed. You can create a raw string by prefixing the string with `r` or `R`.

```python
text = r"This is a raw string: \n will not be processed"
print(text)
# Output: This is a raw string: \n will not be processed
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
