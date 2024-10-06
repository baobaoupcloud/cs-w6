---
title : "Loops"
date :  "`r Sys.Date()`" 
weight : 4 
chapter : false
pre : " <b> 4. </b> "
---
Loops are used to repeat a block of code multiple times.

### `for` Loop

Iterates over a sequence (like a list or range).

```python
for i in range(3):
    print("Hello!")  # Prints "Hello!" 3 times
```

### `while` Loop

Repeats as long as a condition is true.

```python
i = 0
while i < 3:
    print("Hello!")  # Prints "Hello!" 3 times
    i += 1  # Increment i by 1 each time

```

### Difference from C

- No need for initialization and increment statements within the `for` loop.
- Indentation is used instead of curly braces `{}`.