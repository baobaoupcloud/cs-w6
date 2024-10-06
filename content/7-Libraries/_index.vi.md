---
title : "Thư viện"
date :  "`r Sys.Date()`" 
weight : 7 
chapter : false
pre : " <b> 7. </b> "
---
Python có một tập hợp lớn các thư viện mở rộng chức năng. Một thư viện là tập hợp mã được viết sẵn mà chúng ta có thể sử dụng để thực hiện các tác vụ thông dụng.

Ví dụ: Xử lý ảnh bằng PIL

```python
from PIL import Image, ImageFilter

# Mở một ảnh
image = Image.open("example.jpg")

# Áp dụng bộ lọc làm mờ
blurred_image = image.filter(ImageFilter.BLUR)

# Lưu ảnh đã chỉnh sửa
blurred_image.save("blurred_example.jpg")
```

**Sử dụng các thư viện bên thứ ba**

Chúng ta có thể cài đặt và sử dụng các thư viện bên ngoài bằng lệnh `pip`.

```bash
pip install face_recognition
```