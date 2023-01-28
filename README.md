# Homework - Camera Calibration with OpenCV
Homework of Computer Vision Course

The aim of this homework is to understand how camera calibration works on OpenCV by using the checkerboard pattern and taking pictures from two different angles.
The dataset used contains 28 pictures, 14 from left angle and 14 from right angles taken by Canon 750d camera.

# What is camera calibration?
The term Camera Calibration[1], or camera resectioning, means estimating the parameters of a lens and image sensor of an image or camera. Using these parameters we can correct the lens distortion, measure the size of an object in world units, or determine the location of the camera in the scene.

## How?
Using a checkerboard pattern[2] of 9 rows, 6 columns and a square size of 24 millimeters is possible to calibrate the two cameras.
![pattern](https://user-images.githubusercontent.com/82369153/215277317-4d7c0fe8-f5e4-44e7-a1ad-bd37a3c0106d.png)

The checkerboard pattern has been printed and applyied on a white box, then pictures have been taken using two Canon 750d[3], the distance between the two cameras (the baseline) is about 116cm but as you can see from the photographic set the camera on the right has a different angle and also it about 10cm further back than the camera on the left.
![photographic_set](https://user-images.githubusercontent.com/82369153/215277340-8236f820-6e28-46c0-bb0b-a2eebc9925e1.jpg)

# References
[1] [Camera calibration tutorial for Python+OpenCV](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_calib3d/py_calibration/py_calibration.html#calibration)

[2] [OpenCv, Checkerbord pattern](https://github.com/opencv/opencv/blob/master/doc/pattern.png)

[3] [Canon EOS 750D](https://en.wikipedia.org/wiki/Canon_EOS_750D)
