# Image Instance Segementation using a Mask Regional-Convolutional Neural Network
#### [instance_segmentation.py](https://github.com/rainarit/Image-Instance-Segmentation/blob/master/scripts/instance_segmentation.py) #### 
__Completed :white_check_mark:__

This is a Python script which is able to extract local image descriptors and generate a spatial feature map and a fully convolution classification and up-sampling network that takes as input the encoded expression and the spatial feature map and outputs a pixel-wise segmentation mask.

<img src='http://g.recordit.co/fTUgWGwohA.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Installation ##
### Requirements ###
The following software libraries/frameworks should be installed:
* [Python](https://www.python.org/downloads/) 3.3+ or Python 2
* [imutils](https://pypi.org/project/imutils/) library
* [time](https://docs.python.org/2/library/time.html) library
* [NumPy](https://numpy.org/) package
* [cv2](https://pypi.org/project/opencv-python/) package
### Installation Options ###
The libraries and frameworks displayed above could be installed in the following direction:

`pip3 install 'framework/library'`
## Usage ##
1. Download [facial_landmarking.py](https://github.com/rainarit/FacialLandmarking/blob/master/facial_landmarking.py). 
2. Go to your Python IDLE and insert: 
`python3 instance_segmentation.py`
