# Basics-of-Python-Programming
This repository is aimed at learning the basics of Python Programming Language


# Table of Contents
1. [Variable](#variable)
2. [Data Types](#data-types)
3. [Operators](#operators)
4. [Expression](#Expression)



# Variable

## Dynamic Typing:
```Python
x = 10          # Integer
name = "Alice"  # String
pi = 3.14       # Float
is_active = True  # Boolean
```

## Reassignment:
```Python
x = 10      # Integer
x = "Ten"   # Now a String
```

## Descriptive Names:
```Python
user_age = 25
total_price = 100.50
```

## Naming Conventions:
- Use descriptive names to make your code readable
```Python
user_age = 25
total_price = 100.50
```
- Variable names must start with a letter or an underscore _, but cannot start with a number.
- Avoid using reserved keywords (e.g., if, for, while) as variable names.
- Use snake_case for multi-word variable names (e.g., user_name, total_amount).

## Multiple Assignments:
Python allows assigning multiple variables in a single line.
```Python
x, y, z = 1, 2, 3
```

You can also assign the same value to multiple variables:
```Python
a = b = c = 5
```

## Printing Variables:
Use the print() function to display variable values.

```Python
name = "Alice"
age = 25
print("Name:", name)
print("Age:", age)
```

### Output

```Python
Name: Alice  
Age: 25
```

# Data Types
Python variables can store different types of data. These data types include:
1. **Integer `(int)`:** Whole numbers
```Python
age = 30
```

2. **Floating Point `(float)`:** Decimal numbers
```Python
price = 19.99
```

3. **String `(str)`:** Textual data
```Python
name = "Alice"
```

4. **Boolean `(bool)`:** True or False values
```Python
is_active = True
```

5. **List, Tuple, Dictionary:** Collections of data
```Python
numbers = [1, 2, 3]  # List
coordinates = (4, 5)  # Tuple
user = {"name": "Alice", "age": 25}  # Dictionary
```

# Operators

## Arithmetic Operators
```Python
a = 10
b = 3
print(a + b)    # Output: 13
print(a ** b)   # Output: 1000 (10 raised to the power of 3)
```

## Comparison Operators
```Python
print(a > b)    # Output: True
print(a == 10)  # Output: True
```

## Logical Operators
```Python
print(a > 5 and b < 5)  # Output: True
print(not(a < 5))       # Output: True
```

## Assignment Operators
x = 5
x += 3
print(x)        # Output: 8

## Membership Operators
```Python
fruits = ["apple", "banana", "cherry"]
print("banana" in fruits)    # Output: True
print("grape" not in fruits) # Output: True
```

# Expression
Example of an expression:
```Python
2 + 3   # This expression evaluates to 5
a * b   # If a = 4 and b = 5, this evaluates to 20
```

## Examples of Expressions

- **Arithmetic Expression:**
```Python
result = (4 + 5) * 2  # Evaluates to 18
```

- **Logical Expression:**
```Python
is_valid = (5 > 2) and (3 < 4)  # Evaluates to True
```

- **String Expression:**
```Python
full_name = "John" + " " + "Doe"  # Evaluates to "John Doe"
```

- **Lambda Expression:**
```Python
add = lambda x, y: x + y
print(add(3, 4))  # Evaluates to 7
```
