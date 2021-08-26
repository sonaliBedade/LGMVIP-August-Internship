# Image to Pencil Sketch with Python

This program converts an image of RGB format to a pencil-sketched one.

### Steps followed:
1. The original image is read
1. The original image is converted to grayscale
1. The grayscale image is inverted
1. The inverted image is blurred using GaussianBlur
1. The blurred image is inverted again
1. The two images are combined to form pencil sketch.

The image used is stored in the 'Image' folder

Reference: https://thecleverprogrammer.com/2020/09/30/pencil-sketch-with-python/