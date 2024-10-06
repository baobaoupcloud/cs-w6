---
title : "Functions"
date :  "`r Sys.Date()`" 
weight : 5 
chapter : false
pre : " <b> 5. </b> "
---
### Functions
Functions are reusable blocks of code that perform a specific task. We define a function using the `def` keyword.

```python
# Define function greet
def greet(name):
    print(f"Hello, {name}")

greet("Alice")  # Calls the function and prints "Hello, Alice"

```

### Parameters and Return Values

We can pass values to a function and get a result using the `return` statement.

```python
def add(x, y):
    return x + y

result = add(5, 3)  # Returns 8
print(result)
```