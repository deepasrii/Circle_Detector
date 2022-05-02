# Circle Detector using HoughCircles

Here, I need to find a solution for the given image, to find whether the image has a circular region and if so evaluate if the given pixel is inside that circular region.

given, the Input: image, (x,y)

check if the pixel coordinate (x,y) is inside or outside the circular region,If a circular region is present.

Import libraries cv2, numpy and matplotlib. Using opencv, upload the image and convert it into grayscale. Then, gaussianblur is used to blur the image because hough circle method works better with the blurred images. HoughCircles function is used to detect circles in the image by giving the required parameters.

To check whether the given pixel coordinates are inside or outside, the General Equation for a Circle denotes:

(x - a)^2 + (y - b)^2 = r^2 where, (a,b) - coordinates of the center of the circle, r - radius of the circle.

Finally, the circle_detector detects the circle in an input image and outlines it in green.
