---
title : "Data Structures"
date :  "`r Sys.Date()`" 
weight : 6 
chapter : false
pre : " <b> 6. </b> "
---
Python provides built-in data structures that simplify storing and manipulating data.

### 1. Lists

Lists are used to store multiple items in a single variable.

```python
fruits = ["Apple", "Banana", "Cherry"]
print(fruits[0])  # Outputs: Apple
```

- Lists are created using square brackets `[]`.
- We can add elements using `append()`.

```python
fruits.append("Orange")  # Adds "Orange" to the list
```

### 2. Dictionaries

Dictionaries store key-value pairs.

```python
person = {"name": "Alice", "age": 25}
print(person["name"])  # Outputs: Alice
```

- Created using curly braces `{}`.
- Access values using keys, like `person["name"]`.