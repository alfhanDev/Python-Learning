# Variable Names

A variable can have a short name (like `x` or `y`) or a more descriptive name (such as `age`, `car_name`, or `total_volume`).

## Rules for Python Variables

- A variable name must start with a letter or an underscore (`_`)
- A variable name cannot start with a number
- A variable name can only contain alphanumeric characters and underscores (`A–Z`, `a–z`, `0–9`, `_`)
- Variable names are case-sensitive (`age`, `Age`, and `AGE` are different variables)
- A variable name cannot be a Python keyword

## Examples

### Legal Variable Names

    myvar = "John"
    my_var = "John"
    _my_var = "John"
    myVar = "John"
    MYVAR = "John"
    myvar2 = "John"

> Remember: variable names are case-sensitive.

## Multi-Word Variable Names

Variable names with more than one word can be harder to read.  
There are several common conventions to improve readability.

### Camel Case

Each word starts with a capital letter except the first:

    myVariableName = "John"

### Pascal Case

Each word starts with a capital letter:

    MyVariableName = "John"

### Snake Case

Each word is separated by an underscore:

    my_variable_name = "John"
