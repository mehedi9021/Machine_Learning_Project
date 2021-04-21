# Face Detection using Python and OpenCV with Webcam
<p align="justify">This project uses LBPH (Local Binary Patterns Histograms) Algorithm to detect faces. It labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.

Approach/Algorithms used:<br>
LBPH uses 4 parameters :<br>
a. Radius: the radius is used to build the circular local binary pattern and represents the radius around the central pixel.<br>
b. Neighbors : the number of sample points to build the circular local binary pattern.<br>
c. Grid X : the number of cells in the horizontal direction.<br>
d. Grid Y : the number of cells in the vertical direction.<br>
The model built is trained with the faces with tag given to them, and later on, the machine is given a test data and machine decides the correct label for it.

Requirements:<br>
Python<br>
OpenCV<br>
Numpy<br>
Haarcascade Frontal face classifiers
