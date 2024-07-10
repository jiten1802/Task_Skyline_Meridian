# Skyline Meridian - AI/ML Internship Task
This project is designed to separate the central cut-out area through which the hair is visible. The task involves using computer vision techniques with OpenCV.

## Steps Involved:
1. Installation of necessary libraries like NumPy, OpenCV, Matplotlib.
2. Read the image using cv2.imread('')
3. Reverse the colour channels
4. Convert the image to gray scale image
5. Apply binary threshhold to get a binary (B/W) image
6. Detect contours on the binary image and draw them
7. Create a mask of same dimension as that of the gray scale image
8. Find the largest contour and draw it on the mask in white colour with thickness = cv2.FILLED
9. Use 'bitwise and' operation on the image and the mask to extract the central are from image
10. Save the image using cv2.imwrite() and display the result

