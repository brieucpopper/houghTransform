# houghTransform
An implementation of hough transform for circle detection and line detection with a python notebook and OpenCV.
This was a project that was part of my Computer Vision course at Georgia Tech.
![ima1](https://github.com/brieucpopper/houghTransform/assets/102361078/a93b9cbc-1748-492c-a088-12c36fd5df96)

This image shows the final result of a "challenging" instance of circle detection, as the background isn't uniform and the circles don't all have the same radius. My algorithm almost got every circle right but we still see a problem in the bottom right part of the image.

![ima2](https://github.com/brieucpopper/houghTransform/assets/102361078/c519058b-a3b4-4acc-a96b-9072783bd50f)

This image shows the top 20 lines found in this image, where an interesting challenge was to try to detect the pens edges.
![ima3](https://github.com/brieucpopper/houghTransform/assets/102361078/97723e1d-8b90-4543-bada-05429d52f8cc)

This is the edge image that was obtained with a canny applied to the image.
![ima4](https://github.com/brieucpopper/houghTransform/assets/102361078/25ca41fd-263e-4117-b9d9-aebd9418ba44)


And this is a representation of the Hough space that is computed, and where the different intersections represent lines (or circles, depending on the case)



To sum up, I discovered the concepts of edge extraction and how to implement the Hough transform algorithm for line and circle extraction.

The .ipynb file explains a bit the code and the theory behind it. (It is a bit messy though)
