#Design Procedures

# Introduction #

**Design and Implementation Procedures**
  1. Achieve communication between the Android device and NXT via Bluetooth:
    * Forward commands from Android device to NXT
    * Read sensor data from NXT with Android device
  1. Implement image operations on the camera input with Android SDK functionality or alliteratively OpenCV for Android:
    * Perform face detection on video stream from camera
    * Capture images from stream where a human face was detected
    * Process captured image with facial recognition, comparing with another given image
  1. Use sensor read input to avoid obstacles in the robot's course and Manipulate the robot into position to take appropriate picture
    * Change the Android device's orientation and elevation
    * Use body recognition to adjust capture position
  1. Automate SMS confirmation when the requested matching face is found
  1. Allow Wifi streaming of processing operations (Optional)


# Details #
<a href='http://i.imgur.com/oKfAbIY.png'>
<img src='http://i.imgur.com/oKfAbIY.png' title='Step 1' width='70%' height='70%' /></a>
<a href='http://i.imgur.com/LktlBGQ.png'>
<img src='http://i.imgur.com/LktlBGQ.png' title='Step 2' width='70%' height='70%' /></a>
<a href='http://i.imgur.com/FRCt6W2.png'>
<img src='http://i.imgur.com/FRCt6W2.png' title='Step 3' width='70%' height='70%' /></a>
<a href='http://i.imgur.com/r1grmy3.png'>
<img src='http://i.imgur.com/r1grmy3.png' title='Step 4' width='70%' height='70%' /></a>
<a href='http://i.imgur.com/ehBsTzB.png'>
<img src='http://i.imgur.com/ehBsTzB.png' title='Step 5' width='70%' height='70%' /></a>