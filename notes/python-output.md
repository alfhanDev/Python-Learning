# Python Output and Print

## Print Text

The print() function is used to display text or output values.

### Example
print("Hello World!")

You can use print() as many times as you want. Each call prints on a new line.

### Example
print("Hello World!")
print("I am learning Python.")
print("It is awesome!")

---

## Double Quotes

Text in Python must be placed inside quotes. You can use either double quotes " " or single quotes ' '.

### Example
print("This will work!")
print('This will also work!')

If you forget to use quotes, Python will give an error.

### Example
print(This will cause an error)
Result:
SyntaxError: invalid syntax

---

## Print Without a New Line

By default, print() ends with a new line.
To print multiple values on the same line, use the end parameter.

### Example
print("Hello World!", end=" ")
print("I will print on the same line.")

There is a space after end=" " to make the text easier to read.

---

# Python Output Numbers

## Print Numbers

You can use print() to display numbers. Numbers are not placed inside quotes.

### Example
print(3)
print(358)
print(50000)

You can also do math inside print().

### Example
print(3 + 3)
print(2 * 5)

---

## Mix Text and Numbers

You can combine text and numbers in one print() call by separating them with commas.

### Example
print("I am", 35, "years old.")
