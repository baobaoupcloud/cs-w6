---
title : "Lập trình hướng đối tượng"
date :  "`r Sys.Date()`" 
weight : 9 
chapter : false
pre : " <b> 9. </b> "
---
Lập trình hướng đối tượng (Object-Oriented Programming - OOP) là một phương pháp lập trình dựa trên khái niệm "đối tượng" (object), giúp mô phỏng các thực thể trong thế giới thực và tổ chức mã nguồn theo cách trực quan và logic hơn

Python hỗ trợ tạo các lớp và đối tượng để biểu diễn các thực thể trong thế giới thực.

Ví dụ, các chuỗi (`strs`) trong Python có các **phương thức tích hợp sẵn**. Do đó, chúng ta có thể sửa đổi đoạn mã như sau:

```python
# Toán tử logic, sử dụng danh sách
from cs50 import get_string

# Nhắc người dùng đồng ý
s = get_string("Bạn có đồng ý không? ").lower()

# Kiểm tra xem người dùng có đồng ý không
if s.lower() in ["y", "yes"]:
    print("Đồng ý.")
elif s.lower() in ["n", "no"]:
    print("Không đồng ý.")
```

Giá trị ban đầu của `s` đã được **ghi đè** bằng kết quả của `s.lower()`.
