# Python Statements

## What is a Statement?
- A computer program is a list of instructions for the computer to execute.
- In Python, each instruction is called a statement.
- A statement usually ends at the end of a line.

### Example
print("Python is fun!")

Python knows this is one complete statement without needing a semicolon.

---

## Execution Order
- Python executes statements from top to bottom, one after another.

### Example
print("Hello World!")
print("Have a good day.")
print("Learning Python is fun!")

Execution order:
1. Prints "Hello World!"
2. Prints "Have a good day."
3. Prints "Learning Python is fun!"

---

## Semicolons in Python
- Semicolons are optional. They allow multiple statements on one line.
- This is rarely used because it reduces readability.

### Example
print("Hello"); print("How are you?"); print("Bye bye!")

If two statements are placed on the same line with no semicolon, Python raises an error.

### Example
print("Python is fun!") print("Really!")
Result:
SyntaxError: invalid syntax

Best Practice: Put each statement on its own line to keep code easy to understand.

---

## Compound Statements
Some statements span multiple lines. Examples include if, while, for, and function definitions.
