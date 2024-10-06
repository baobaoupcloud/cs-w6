---
title : "Conditionals"
date :  "`r Sys.Date()`" 
weight : 3 
chapter : false
pre : " <b> 3. </b> "
---
Conditionals are used to make decisions in our program using `if`, `elif`, and `else` statements.

```python
x = 5
y = 10

if x < y:
    print("x is less than y")
elif x > y:
    print("x is greater than y")
else:
    print("x is equal to y")

```

- **Note**: Indentation is critical in Python. Each code block is defined by its indentation.

**Differences from C**:

- No curly braces `{}`.
- No need for parentheses `()` around the condition.
- Use a colon `:` after the condition.