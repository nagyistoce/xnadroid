**_Yarmouk, 2013_**
**Facial recognition project using an Android powered device mounted on a Lego NXT Robot**.

**Features**
  * Android device application that will perform face detection and facial recognition of a  given face.
  * Robot system that is capable of obstacle avoidance and manipulation through an inhabited terrain.
  * SMS notification of of location coordinates, if SMS is available on device.
  * Video stream over Wifi of ongoing image processing operations.

**Technology**
  1. Android SDK with Eclipse
  1. leJos NXJ toolkit for NXT [(Website) ](http://lejos.sourceforge.net/)
  1. OpenCV library for Android
  1. Android Native Design Kit (NDK)

**Initial Procedure**
  * Design and build Lego NXT robot capable of mounting an Android device, given specific device dimensions.
  * The robot must allow for 360 degrees FOV for the Android device camera.
  * Flash LeJos NXJ JVM onto NXT Brick.
  * Install the complete SDK for Android at its latest available version (API 17 as of Feb, 24, 2013)
  * Create a project repository.

---

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
  1. Allow Wifi streaming of processing operations