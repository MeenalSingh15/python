# What is python and why is it necessary for Data Science ?
Everything is object and it is under a particular class.
Python is high level interpreted programming language that is dynamically typed that is known for its simplicity, readibility and ease of use.
It was created by Guido van Rossam in late 1980s and is one of the most used pragramming language of the world .
It is interpreted language which basically means the code is executed directly withou compilation need which makes it easier to use and detect bugs in addition the script can be used on  multiple platforms withput having to worry about platform specific issues.
It is used in many fields like data science , web development, machine learning and scientific computing.
## IDEs


# Variable 
Variable in python are containers that store data that can belong to any data type available in python.
to assign values in any variable we use '=' operator.
```python
x = 10 #x is a variable that holds a int value  10
s ="hi" #s is a variable that holds a string value'hi'
```
Variables can store any data type and can also change data types during runtime using Typecasting
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
   ```output:output
     This String 
 has been split 
 inot
 multiple lines.
  ```
- \t: Tab character. It moves the cursor to the next tab stop i.e. it adds a space.
```python
  stringspace='This\tString\thas\tbeen\tspaced\tequally.'
  print(stringspace)
```
 ```output:output
     This	String	has	been	spaced	equally.
  ```

- \\: Backslash character. It represents a single backslash.
  ```python
    print("This is a backslash: \\")
  ```
  ```output:output
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
# Operators

# loops 
# if-else  if-elif-else
These are conditional statements 
keyword if is followed by a condition if the condition is true the next code is interpreted otherwise we move to else statement.
elif is another keyword used when we have to check two conditions and else is basically default code to be read if no conditions are met .
 let us see few examples :
 
''Write a Python program that takes a user's input for their current salary and their performance rating (which can be "excellent", "good", "average", or "poor"), and returns their new salary based on the following conditions:

If the performance rating is "excellent", the user's new salary should be 10% more than their current salary. If the performance rating is "good", 
the user's new salary should be 5% more than their current salary. If the performance rating is "average", the user's new salary should be the same as their current salary. 
If the performance rating is "poor", the user's new salary should be 2% less than their current salary. else "Invalid performance rating."

''
```python
current_salary = int(input("current:"))
rating= input("rating:")

if rating =='excellant':
  new == current_salary*1.10
elif rating =="good":
  new == current_salary*1.05

print(new) ```


``` python
output:
current:88
rating:good
1```











