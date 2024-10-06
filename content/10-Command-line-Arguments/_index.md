---
title : "Command-line Arguments"
date :  "`r Sys.Date()`" 
weight : 10 
chapter : false
pre : " <b> 10. </b> "
---
Command-line arguments allow us to pass inputs to our script through the terminal.

## **Example:**

```python
from sys import argv

if len(argv) == 2:
    print(f"Hello, {argv[1]}")
else:
    print("Hello, world")

```

- `argv` is a list that contains command-line arguments.
- Use `sys.argv[1]` to access the first argument.