# "Real-Time Face, Eye, and Body Detection Using OpenCV Haar Cascades"
This project demonstrates how to detect faces,Eyes and Bodies of humans in images, videos, and real-time video streams using the webcam. It utilizes OpenCV's pre-trained Haar Cascade classifiers for detecting both Faces and Eyes.

# Introduction
This project uses OpenCV to detect Faces and Eyes using Haar Cascade Classifiers. The program can be used to:

Detect faces and eyes in static images, video files and can
perform real-time face and eye detection using the webcam of your devices.

# Features
* Detects the faces first using "detectMultiScale" method.
* For each detected face, it detects eyes within the face region.
* Pops up the webcam, it can recognize the faces, eyes and bodies in real-time.
* Rectangles are drawn around both the faces and the eyes for visualization.

# Installation
1. Clone the repository
2. Install the necessary dependencies
3. Ensure that OpenCV is installed
4. Download the Haar Cascade Classifier XML files from OpenCV's GitHub repository
5. Make sure that the Face Haarcascade Classifier is in the same location as in the Eye Haar Cascade.
6. Load the face and eye classifiers using CascadeClassifiers.

### Files needed to download (Haarcascade classifiers)
* Haar cascade for face detection
  https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml
* Haar cascade for Eye detection
  https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye.xml
* Haar cascade for Body Classifiers
* https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_fullbody.xml

### Example of Installation:
![image](https://github.com/user-attachments/assets/b08e44fb-e438-4f75-b205-6beff78f4e42)


# Requirements
Python 3.x
OpenCV (cv2)
Numpy
Webcam (for real-time detection)


# Load a JPG image using 'cv2' 

![image](https://github.com/user-attachments/assets/db20c93b-94bc-4762-a2fd-4839fa40cfec)


# Results of Facial and Eye detection using OpenCV Haarcascades


