# Python Output / Print

## Print Text

You can use the print() function to display text or output values.

### Example:
    
    print("Hello World!")

You can use the print() function as many times as you want. Each call prints text on a new line by default:

### Example
    
    print("Hello World!")
    print("I am learning Python.")
    print("It is awesome!")

---

## Double Quotes

Text in Python must be inside quotes. You can use either " double quotes or ' single quotes.

### Example:
    
    print("This will work!")
    print('This will also work!')

If you forget to put the text inside quotes, Python will give an error.

### Example
    
    print(This will cause an error)

### Result:
    
    SyntaxError: invalid syntax

---

## Print Without a New Line

By default, the print() function ends with a new line.  
If you want to print multiple words on the same line, you can use the end parameter.

### Example:
    
    print("Hello World!", end=" ")
    print("I will print on the same line.")

There is a space after end=" " to make the text easier to read.

---

# Python Output Numbers

## Print Numbers

You can also use the print() function to display numbers.  
Unlike text, numbers are not placed inside quotes.

### Example:
    
    print(3)
    print(358)
    print(50000)

You can also do math inside the print() function.

### Example:
    
    print(3 + 3)
    print(2 * 5)

---

## Mix Text and Numbers

You can combine text and numbers in one output by separating them with commas.

### Example:
    
    print("I am", 35, "years old.")
