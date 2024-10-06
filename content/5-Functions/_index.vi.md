---
title : "Hàm"
date :  "`r Sys.Date()`" 
weight : 5 
chapter : false
pre : " <b> 5. </b> "
---
Hàm là những khối mã có thể tái sử dụng và thực hiện một nhiệm vụ cụ thể. Chúng ta khai báo hàm bằng từ khóa `def`.

```python
# Định nghĩa hàm chào
def chao(name):
    print(f"Xin chào, {name}")

chao("Alice")  # Gọi hàm và in ra "Xin chào, Alice"
```