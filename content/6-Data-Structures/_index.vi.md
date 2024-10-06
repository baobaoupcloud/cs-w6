---
title : "Cấu trúc dữ liệu"
date :  "`r Sys.Date()`" 
weight : 6 
chapter : false
pre : " <b> 6. </b> "
---
Python cung cấp nhiều cấu trúc dữ liệu tích hợp giúp lưu trữ và xử lý dữ liệu dễ dàng.

#### 1. Danh sách (List)

Danh sách dùng để lưu trữ nhiều mục trong một biến duy nhất.

```python
fruits = ["Táo", "Chuối", "Anh đào"]
print(fruits[0])  # Xuất ra: Táo
```

- Danh sách được tạo bằng dấu ngoặc vuông `[]`.
- Có thể thêm phần tử bằng `append()`.

```python
fruits.append("Cam")  # Thêm "Cam" vào danh sách
```

#### 2. Từ điển (Dictionary)

Từ điển lưu trữ các cặp khóa-giá trị.

```python
person = {"ten": "Alice", "tuoi": 25}
print(person["ten"])  # Xuất ra: Alice
```

- Tạo từ điển bằng dấu ngoặc nhọn `{}`.
- Truy cập giá trị bằng cách sử dụng khóa, như `person["ten"]`.