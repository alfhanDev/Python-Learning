# Python Syntax

## Execute Python Syntax
Python syntax can be executed directly from the command line.

---

## Python Indentation
- Indentation refers to the spaces at the beginning of a code line.
- Where in other programming languages the indentation is for readability only, in Python it is very important.
- Python uses indentation to indicate a block of code.

### Example:
```python
if 5 > 2:
    print("Five is greater than two!")
```

### Python will give you an error if you skip the indentation

#### Example  
Syntax Error (on purpose):
```
if 5 > 2:
print("Five is greater than two!")
```

### The number of spaces is up to you as a programmer.  
The most common use is four, but it has to be at least one.

#### Example:
```python
if 5 > 2:
    print("Five is greater than two!")    # 4 spaces

if 5 > 2:
        print("Five is greater than two!")  # 8 spaces
```

---

## Python Variables
- In Python, variables are created when you assign a value to them.
- Python has no command for declaring a variable.

### Example:
```python
x = 5
y = "Hello, World!"
```

---

## Comments
- Python has commenting capability for in-code documentation.
- Comments start with `#`, and Python ignores the rest of the line.

### Example:
```python
# This is a comment
print("Hello, World!")
```
