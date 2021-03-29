# Not Planning to make this anytime soon! Comment if you want to contribute.

# WinCam
WinCam, the perfect module to handle picture and video on Windows.

Main Features:
- Get a list of Cameras connected to a device
- Recieve Video Feed from a selected Camera
- Record Video Feed from a selected Camera
- Capture Photos from a selected Camera
- and More!

And don't worry, if there is a feature you would like to add that isn't already included, you can contribute to this project!

# Simple Guide

To get video feed from a camera, and show it in a window, use this simple script.
```py
import wincam

wincam.getVideo(1)
wincam.showVideo()
```


To get a list of cameras
```py
import wincam

cameras = wincam.getCameraList()
print(cameras)
```

This is my Output:
```['0. Panasonic TY-CC20W', '1. Logitech C920S', '2. HD 1080P Webcam']```


