# cg-lab1

## Read an image from `images/`

### Display the image

![Sample image](images/image.png)

Use Python and Pillow in a notebook or script:

```python
from PIL import Image

img = Image.open("images/image.png")
img
```

If you prefer OpenCV:

```python
import cv2

img = cv2.imread("images/image.png")
# OpenCV loads BGR by default; convert to RGB for display.
img_rgb = cv2.cvtColor(img, cv2.COLOR_BGR2RGB)
img_rgb
```
