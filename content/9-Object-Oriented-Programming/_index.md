---
title : "Object-oriented Programming"
date :  "`r Sys.Date()`" 
weight : 9
chapter : false
pre : " <b> 9. </b> "
---
Object-oriented Programming (OOP) is a programming paradigm based on the concept of "objects". It helps structure code by grouping related properties and behaviors into units (objects), making the code more modular, readable.

Python supports creating classes and objects to represent real-world entities.

In C, we could create a `struct` where we could associate multiple variables inside a single self-created data type. In Python, we can do this and also include functions in a self-created data type. When a function belongs to a specific *object*, it is known as a *method*

For example, `strs` in Python have a built-in *methods*. Therefore, we could modify the code as follows:

```python
# Logical operators, using lists
from cs50 import get_string

# Prompt user to agree
s = get_string("Do you agree? ").lower()

# Check whether agreed
if s.lower() in ["y", "yes"]:
    print("Agreed.")
elif s.lower() in ["n", "no"]:
    print("Not agreed."
```

Notice how the old value of `s` is overwritten with the result of `s.lower()`