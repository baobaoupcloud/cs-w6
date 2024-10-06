---
title : "Điều kiện"
date :  "`r Sys.Date()`" 
weight : 3 
chapter : false
pre : " <b> 3. </b> "
---
Câu lệnh điều kiện được dùng để đưa ra quyết định trong chương trình bằng cách sử dụng các từ khóa `if`, `elif`, và `else`.

```python
x = 5
y = 10

if x < y:
    print("x nhỏ hơn y")
elif x > y:
    print("x lớn hơn y")
else:
    print("x bằng y")
```

- **Lưu ý**: Thụt đầu dòng là rất quan trọng trong Python. Mỗi khối mã được xác định bằng việc thụt đầu dòng.

**Khác biệt so với ngôn ngữ C**:

- Không dùng dấu ngoặc nhọn `{}`.
- Không cần dấu ngoặc đơn `()` bao quanh điều kiện.
- Sử dụng dấu hai chấm `:` sau điều kiện.

### **4. Vòng lặp trong Python**

Vòng lặp được dùng để lặp lại một đoạn mã nhiều lần.

#### Vòng lặp `for`

Duyệt qua một chuỗi (như danh sách hoặc phạm vi số).

```python
for i in range(3):
    print("Xin chào!")  # In ra "Xin chào!" 3 lần
```