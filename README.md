# Basics-of-Python-Programming
This repository is aimed at learning the basics of Python Programming Language


# Table of Contents
1. [Variable](#variable)
2. [Data Types](#data-types)
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

