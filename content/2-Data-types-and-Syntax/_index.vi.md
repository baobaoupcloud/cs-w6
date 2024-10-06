---
title : "Kiểu dữ liệu và Cú pháp"
date :  "`r Sys.Date()`" 
weight : 2 
chapter : false
pre : " <b> 2. </b> "
---
### **1. Các kiểu dữ liệu trong Python**

- Chúng ta không cần chỉ định kiểu dữ liệu như `int`, `float`, `string`. Python tự động hiểu và xử lý.

    ```python
    x = 10        # Số nguyên (Integer)
    y = 20.5      # Số thực (Float)
    name = "John" # Chuỗi ký tự (String)
    ```

- **Các kiểu dữ liệu phổ biến**:
    - `int`: Số nguyên.
    - `float`: Số thập phân.
    - `str`: Văn bản.
    - `bool`: Đúng hoặc Sai.

- **Cú pháp cơ bản**
    - Dùng hàm `print()` để hiển thị kết quả.
    - Dùng hàm `input()` để lấy dữ liệu đầu vào từ người dùng.

    ```python
    name = input("Tên của bạn là gì? ")  # Nhập dữ liệu
    print(f"Xin chào, {name}")  # Hiển thị kết quả sử dụng f-string
    ```
