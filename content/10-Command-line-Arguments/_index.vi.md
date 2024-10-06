---
title : "Đối số dòng lệnh"
date :  "`r Sys.Date()`" 
weight : 10 
chapter : false
pre : " <b> 10. </b> "
---
Đối số dòng lệnh cho phép chúng ta truyền đầu vào cho tập lệnh thông qua terminal.

Ví dụ:

```python
from sys import argv

if len(argv) == 2:
    print(f"Xin chào, {argv[1]}")
else:
    print("Xin chào bạn!")
```

- `argv` là danh sách chứa các đối số dòng lệnh.
- Sử dụng `sys.argv[1]` để truy cập đối số đầu tiên.
