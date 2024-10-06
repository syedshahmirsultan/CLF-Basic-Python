# Welcome to the CLF  1st year Unit 3 Python Repository

## Table of Contents
- [Print](#print)
- [Variable Declaring](#variable-declaring)
- [Input()](#input)
- [Range()](#range)
- [For Loop](#for-loop)
- [List](#list)
- [Type()](#type)
- [Eval()](#eval)
- [Len()](#len)
- [Sum()](#sum)
- [Max()](#max)
- [Min()](#min)
- [Append()](#append)
- [RandomInt()](#randomint)

---

## Print
The `print()` function is used to display output to the console.
```python
print("Hello, World!")  # This will print: Hello, World!
```

## Variable Declaring
Variables are used to store data values. You can declare a variable by assigning a value to it.
```python
name = "Shahmir"  # Here, 'name' is a variable storing the string "Shahmir".
```

## Input()
The `input()` function is used to take user input. The input is always returned as a string.
```python
age = input("Enter your age: ")  # User is asked to enter their age.
```

## Range()
The `range()` function generates a sequence of numbers. It can be used in loops.
```python
for i in range(1, 6):
    print(i)  # This will print numbers from 1 to 5.
```

## For Loop
A `for` loop is used to iterate over a sequence (like a list or a range).
```python
for i in range(5):
    print(i)  # This will print numbers from 0 to 4.
```

## List
A list is a collection of items. Lists are ordered and editable.
```python
my_list = [1, 2, 3, 4, 5]  # A list of integers.
```

## Type()
The `type()` function returns the type of an object.
```python
print(type(my_list))  # This will print: <class 'list'>
```

## Eval()
The `eval()` function parses the expression given to it and executes it.
```python
result = eval("3 + 5")  # This will evaluate the expression and store 8 in result.
```

## Len()
The `len()` function returns the number of items in an object.
```python
print(len(my_list))  # This will print: 5
```

## Sum()
The `sum()` function returns the sum of all items in an iterable.
```python
total = sum(my_list)  # This will store the sum of the list in 'total'.
```

## Max()
The `max()` function returns the largest item in an iterable.
```python
print(max(my_list))  # This will print: 5
```

## Min()
The `min()` function returns the smallest item in an iterable.
```python
print(min(my_list))  # This will print: 1
```

## Append()
The `append()` method adds an item to the end of a list.
```python
my_list.append(6)  # This will add the number 6 to the end of my_list.
```

## RandomInt()
The `randint()` function from the `random` module generates a random integer within a specified range.
```python
from random import randint
random_number = randint(1, 10)  # This will generate a random number between 1 and 10.
```

---
