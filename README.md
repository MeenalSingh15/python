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

````
# Typecasting
Typecasting in Python refers to the process of converting a variable from one data type to another. This is often necessary when you want to perform operations that require variables of compatible types.
These are of two types
Implicit Type Conversion: Python automatically performs some type conversions, known as implicit type conversion or coercion, when it's safe to do so. 
For example, when you add an integer to a floating-point number, Python converts the integer to a float.
```python
x = 10
y = float(x)  # Explicitly convert integer to float
print(type(y))
a=10
b=2.5
c=a*b
print(type1(c)) #implicit conversion of data type to float
```
``` output-
<class 'float'>
<class 'float'>
```

# list 
lists are mutable, meaning their elements can be changed after the list is created.
Lists are created using square brackets '[]' and commas ',' to separate elements.
## list methods
 Lists in Python come with various built-in methods for manipulation, such as append(), extend(), insert(), remove(), pop(), index(), count(), sort(), and reverse(),etc
 # tuple
 A tuple in Python is a data structure similar to a list, but it is immutable, meaning its elements cannot be changed after the tuple is created. Tuples are defined using parentheses () and commas , to separate elements. 
Tuples are created using parentheses '()' and commas ','. These are accesed by indexing
Unlike lists, tuples are immutable, which means you cannot change, add, or remove elements after the tuple is created.
To create a single-element tuple, you need to include a trailing comma after the element, even though parentheses alone can create a tuple.
ou can pack multiple values into a tuple and unpack them into individual variables.
uples are often used when you want to store a collection of items that should not be changed, such as coordinates, configurations, or database records.

Tuples are useful for situations where you want to ensure that the data remains constant and cannot be accidentally modified.
```python
my_tuple = (1, 2, 3, 4, 5)
print(my_tuple[0])  # Output: 1
print(my_tuple[2])  # Output: 3
my_tuple[0] = 10  # This will raise a TypeError
single_element_tuple = (42,)  # Single-element tuple
coordinates = (3, 4)
x, y = coordinates


my_tuple.count(3)  # Returns the number of occurrences of 3 in the tuple
my_tuple.index(4)  # Returns the index of the first occurrence of 4
```

