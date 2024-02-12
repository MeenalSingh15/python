# What is python and why is it necessary for Data Science ?


# Data Types in Python 

Python supports several built-in data types that are commonly used in programming. 
The main data types in Python:

## Numeric Types:
* int: Integer data type i.e number is positive or negative but never a fraction or decimal. 
(e.g., 36, -36).

* float: Floating-point data type is a data type that includes real number that are both whole numbers or fractions .
(e.g., 3.14, -0.5).

## Sequence Types:

* str: String data type
Strings are basically any sequences of characters, which can include letters,symbols,numbers and whitespaces.
In python and most programming languages, strings are enclosed in quotation marks (either single ' or double "). 

For example:
"Hello, world!"
'This is a string.'
"12345"
'Special characters: !@#$%^&*()'

* list: List data type (ordered and mutable sequence).

* tuple: Tuple data type (ordered and immutable sequence).

* Mapping Type:
   *dict: Dictionary data type (unordered collection of key-value pairs).

* Set Types:
   + set: Set data type (unordered collection of unique elements).
   + frozenset: Immutable set.

## Boolean Type:
  + bool: Boolean data type (either True or False).

## None Type:
 + None: Represents the absence of a value or a null value.
   These data types give python flexibility to work on so many types of data and manipulate so many types of data.
   You can use type-specific functions and operators i.e functions and operators designed for a specific type of data  to perform operations on these data types. 
   Python is dynamically typed, meaning you don't need to explicitly declare the data type of a variable it is inferred at runtime.

Examples:
```python
# Numeric types
integer_var = 42
float_var = 3.14

# Sequence types
string_var = "Hello, World!"
list_var = [1, 2, 3]
tuple_var = (4, 5, 6)

# Mapping type
dict_var = {'name': 'John', 'age': 25}

# Set type
set_var = {1, 2, 3}

# Boolean type
bool_var = True

# None type
none_var = None
```
## *Escape characters 
These are special characters used in strings that maybe printable or non printable 
- \n: Newline character. It moves the cursor to the beginning of the next line i.e it adds  a line whereever used

  ```python
  stringsplit='This String \n has been split \n inot\n multiple lines.'
  print(stringsplit)
  ```
- \t: Tab character. It moves the cursor to the next tab stop i.e. it adds a space.
```python
  stringspace='This\tString\t has\t been\tspaced\tequally.'
print(stringspace)
  ```

- \\: Backslash character. It represents a single backslash.
  ```python
  print("This is a backslash: \\")
  ```
  ```output:
 This is a backslash: \
 ```

- \': Single quote character. It represents a single quote within a string.
  ```python
  print("This is a single quote: \'")
  ```
```output:
This is a single quote: '
 ```
- \": Double quote character. It represents a double quote within a string.
   ```python
  print("This is a double quote: \"")
  ```
   ```output:
   This is a double quote: ""
   ```
   
- \b: Backspace character. It moves the cursor one position backward.
 ```python
  print("Backspace: a\bo")
  ```
```output:
 Backspace: o
   ```


