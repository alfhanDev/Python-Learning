# Python Variables – Assigning Multiple Variables

## Assign Multiple Values to Multiple Variables

Python allows you to assign multiple values to multiple variables in a single line.

### Example:
    x, y, z = "Orange", "Banana", "Cherry"
    print(x)
    print(y)
    print(z)

---

## Assign One Value to Multiple Variables

You can assign the same value to multiple variables at once.

### Example:
    x = y = z = "Orange"
    print(x)
    print(y)
    print(z)

---

## Unpacking a Collection

If you have a collection (such as a list or tuple), Python allows you to extract its values into individual variables. This is called **unpacking**.

### Example (Unpacking a List):
    fruits = ["apple", "banana", "cherry"]
    x, y, z = fruits
    print(x)
    print(y)
    print(z)
