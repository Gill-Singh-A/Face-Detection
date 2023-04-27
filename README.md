# Face Detection
A Python Program that uses OpenCV's haarcascade to Detect Faces

## Requirements
Language Used = Python3<br />
Modules/Packages used:
* cv2
* datetime
* optparse
* time
* colorama

## Input
It takes the following arguments from the command that is used to run the Python Program:
* '-i', "--image" : Path to the Image file (If not specified, will take frame from Camera Stream)
* '-c', "--cascade" : Path to cascade File
* '-s', "--scale-factor" : Scale Factor
* '-m', "--min-neighbors" : Minimum Neighbors

## Output
Image/Live Video Stream from the Camera with Detected Faces and number of detected Faces on the Command Line Interface.

### Note
If the output was not what you expected, try to adjust the **scale-factor** and **min-neighbors** value.