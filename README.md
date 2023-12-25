# Image-Resizing-with-Pillow-
Resize an image using the Pillow library (PIL)
from PIL import Image

image = Image.open('input.jpg')
resized_image = image.resize((width, height))

resized_image.save('output.jpg')
