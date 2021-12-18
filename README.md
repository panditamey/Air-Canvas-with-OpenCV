# Air-Canvas-with-OpenCV

A computer vision project based on OpenCV

If you held your finger up in the air, you could draw whatever you wanted. The objective of this post is to build an Air Canvas that can draw anything by simply capturing the motion of a coloured marker with a camera. The marker is a coloured object held at the tip of the finger.
As part of this project, we will use OpenCV's computer vision techniques. 

In general, Python is preferred because of its extensive libraries and easy-to-understand syntax, but it can be implemented in any language that supports OpenCV.
The objective is achieved through the use of colour detection and tracking. After detecting the colour marker, a mask is generated. In this step, the mask produced is subjected to further morphological operations, namely erosion and dilation. Erosion reduces the amount of impurities in the mask, and dilation further restores the eroded main mask.

Requirements: python3 , numpy , opencv installed on your system.

![Capture](https://user-images.githubusercontent.com/75241207/146654497-2bb898e8-8d15-4d23-b103-d367251c3ad5.JPG)
