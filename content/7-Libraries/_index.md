---
title : "Libraries"
date :  "`r Sys.Date()`" 
weight : 7 
chapter : false
pre : " <b> 7. </b> "
---
Python has a vast collection of libraries that extend its functionality. A library is a collection of pre-written code that we can use to perform common tasks.

Example: Image Processing Using PIL

```python
from PIL import Image, ImageFilter

# Open an image
image = Image.open("example.jpg")

# Apply a blur filter
blurred_image = image.filter(ImageFilter.BLUR)

# Save the modified image
blurred_image.save("blurred_example.jpg")

```

**Using Third-Party Libraries**

We can install and use external libraries using the `pip` command.

```bash
pip install face_recognition
```