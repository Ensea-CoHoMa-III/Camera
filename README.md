This file explains the basic on how to access the video streaming of the camera.


# Steps 
1) set the camera to a wifi station,
2) access the ip it gives on the serial port (printed)

## How to set the camera to a wifi station
- Open "CameraAsStation" folder,
- Modify the wifi name and wifi password in "main.cpp"
- Change the COM port in the platformio.ini file (the COm port is shown at the bottom in the middle (orignally written "Auto"), modified by choosing the port)
- Look at the printed message telling you the ip to access the camera
- (the video only shows by pressing "Start stream" at the bottom) 

## How to access printing 
- In order to access the print monitor, there is the need to modify the COM port in the platformio.ini file.
- When uploading code to the camera, wait for the code to finish uploading, then open the serial monitor (in the bottom left in VS code)
- Then you get access to the printed messages.




