# PX4-Gazebo-Opencv
This repo contains how to receive PX4 Gazebo Camera Plugin UDP Video into Opencv.VideoCapture()

This code belongs to https://gist.github.com/patrickelectric/443645bb0fd6e71b34c504d20d475d5a

If you are using another Ground Control Station (like QGC), don't forget to close UDP Video Receiver. Simulation plugin is not multicast stream.


### Steps:

Start simulation gazebo with `make posix gazebo_typhoon_h480`

Start python script with `python opencv-gazebo.py`

### NOTES: 
- I preffered version Python 3.6.9 for another OpenCV implementations.

![Screenshot 1](https://user-images.githubusercontent.com/44507545/70604304-7d424580-1c09-11ea-9a4f-8212e2260ebd.png)
