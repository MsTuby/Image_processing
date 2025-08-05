# Image_processing
Image processing using python 
Libraries:
1. OpenCV
2. Imults (Image Utilities)
3. Numpy (numerical python)

The following series of programs explore object tracking using OpenCV's popular object tracker algorithm- 'kcf' (kernalized correlation filter), and implementation of basic kernels on the video frames for sharpening/ blurring of the selected ROI, along with tracking it!

What is kcf?
kcf or 'kernalized correlation filter' is a correlation filter based tracking algorithm that works on feature extraction from the image. The algorithm learns the correlation filter by performing correlation between the selected ROI and the input image. Compared to other available tracking algorithm by OpenCV, kcf is faster and more suitable for real-time tracking. However, its performance is affected by occlusion.

This repository is a compilation of 3 programs:
program 1: Tracks the selected ROI
program 2: Tracks and sharpens the ROI
program 3: Tracks and blurrs the ROI

Install the necessary packages mentioned in the code at the top
