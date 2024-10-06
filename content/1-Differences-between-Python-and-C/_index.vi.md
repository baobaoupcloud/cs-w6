---
title : "Python và C"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
**1. Không cần biên dịch**

- Trong C, bạn phải biên dịch mã trước khi chạy.
- Trong Python, bạn có thể chạy trực tiếp tập tin mà không cần biên dịch, giúp việc thử nghiệm và gỡ lỗi nhanh hơn.

**2. Cú pháp đơn giản hơn**

- Python loại bỏ các cú pháp không cần thiết như dấu chấm phẩy `;` và dấu ngoặc nhọn `{}` thường thấy trong C.

   Ví dụ mã trong C:

   ```c
   // Mã C
   #include <stdio.h>
   int main(void) {
       printf("Xin chào!\n");
       return 0;
   }
   ```

   Còn đây là mã trong Python:

   ```python
   # Mã Python
   print("Xin chào!")
   ```

**3. Quản lý bộ nhớ tự động**

- Trong C, bạn phải tự cấp phát và giải phóng bộ nhớ.
- Python tự động quản lý bộ nhớ, giảm thiểu lỗi liên quan đến việc quản lý tài nguyên.

**4. Hỗ trợ nhiều kiểu dữ liệu dễ dàng**

- Python cung cấp sẵn các kiểu dữ liệu như danh sách (list), từ điển (dictionary), chuỗi ký tự (string),... giúp việc xử lý trở nên đơn giản hơn so với C, không cần phải triển khai chúng một cách thủ công.