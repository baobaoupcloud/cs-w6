---
title : "Data types and Syntax"
date :  "`r Sys.Date()`" 
weight : 2 
chapter : false
pre : " <b> 2. </b> "
---
- We don’t need to specify data types like `int`, `float`, `string`. Python automatically understands.

    ```python
    x = 10        # Integer
    y = 20.5      # Float
    name = "John" # String
    ```

- **Common Data Types**:
    - `int`: Whole numbers.
    - `float`: Decimal numbers.
    - `str`: Text.
    - `bool`: True or False.

- **Basic Syntax**
    - We use the `print()` function to display output.
    - We use the `input()` function to get input from the user.

    ```python
    name = input("What's your name? ")  # Getting input
    print(f"Hello, {name}")  # Displaying output using an f-string
    ```