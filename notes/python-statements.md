# Python Statements

## Statements
  - A computer program is a list of "instructions" to be "executed" by a computer.
  - In a programming language, these programming instructions are called **"statements"**
  - The following statement prints the text "Python is fun!" to the screen:

### Example:
    print("Python is fun!")

  - In Python, a statement usually ends when the line ends. You do not need to use a semicolon (;) like in many other programming languages (for example, Java or C)

---

## Many Statements
  - Many Python programs contain many statments.
  - The statements are executed one by one, in the same order as they are written:

### Example:
    print("Hello World!")
    print("Have a good day.")
    print("Learning Python is fun!")

### Example explained:

From the example aboe we have three statements:
  - The first statement is executed first (print "Hello World!")
  - Then the second statement is executed (print "Have a good day.")
  - And at last, the third statement is executed (print "Learning Python is fun!)

---

## Semicolons (Optional, Rarely Used)

Semicolons are optional in Python. You can write multiple statements on one line by separating them with ; but this is rarely used because it makes it hard to read

### Example:
    print("Hello"); print("How are you?"); print("Bye bye!")

However if you put two statements on the same line without a separator or (newline or ;), Python will give an error

### Example:
    print("Python is fun!") print("Really!")
### Result:
    SyntaxError: invalid syntax

#### **Best Practice:** Put each statement on its own line so your code is easy to understand.
    
    
    
