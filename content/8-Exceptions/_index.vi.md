---
title : "Ngoại lệ"
date :  "`r Sys.Date()`" 
weight : 8 
chapter : false
pre : " <b> 8. </b> "
---
Ngoại lệ (exception) là các lỗi xảy ra trong quá trình chạy chương trình. Python xử lý ngoại lệ bằng cách sử dụng các khối `try`, `except`.

```python
try:
    x = int(input("Nhập một số: "))
except ValueError:
    print("Đây không phải là số hợp lệ!")
```

- `try`: Đoạn mã mà chúng ta muốn thực thi.
- `except`: Đoạn mã được chạy nếu có lỗi xảy ra.
