# Mouse-Cursor-Detection

### Objective
The objective of this task is to locate the cursor in an image based on a given template.

### Approach:

1. First of all, we are reading the image and template. Convert both to grayscale.

2. To reduce the noise in the image, use the gaussian blur on both of the images.

3. Get the Laplacian transform in order to detect the edge of the image and template.

4. Convert the image into binary using the threshold method.

5. Again, apply the gaussian blur on the detected edges.

6. Perform scaling of the template.

7. Then perform the template matching using the template.

8. Repeat step 6 and 7, until a match is found above a given threshold.

9. Draw the rectangle at the match.
