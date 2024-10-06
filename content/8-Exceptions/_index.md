---
title : "Exceptions"
date :  "`r Sys.Date()`" 
weight : 8 
chapter : false
pre : " <b> 8. </b> "
---
Exceptions are errors that occur during the execution of a program. Python handles exceptions using `try`, `except` blocks.

```python
try:
    x = int(input("Enter a number: "))
except ValueError:
    print("That's not a valid number!")

```

- `try`: The code we want to run.
- `except`: The code that runs if an error occurs.