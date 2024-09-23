# "Real-Time Face, Eye, and Body Detection Using OpenCV Haar Cascades"
This project demonstrates real-time detection of human faces, eyes, and bodies in images, video files, and webcam streams using OpenCV’s pre-trained Haar Cascade classifiers. 
It offers efficient face, eye, and body recognition through both static media and live video streams, utilizing Computer Vision.

# Introduction
This project leverages OpenCV's Haar Cascade Classifiers for detecting faces, eyes, and bodies in various media, including static images, recorded video, and real-time webcam streams. The main objectives of this project include:

* Detecting faces and eyes in images or video files.
* Performing real-time face, eye, and body detection using a webcam.
* Drawing bounding boxes around detected faces, eyes, and bodies for visualization.

# Key Features
* Face and Eye Detection: Faces are detected using the detectMultiScale method. For each detected face, it detects eyes within the face region..
* Real-Time Detection: The system can capture and process frames from a webcam, allowing real-time detection of faces, eyes, and bodies by popping up a window on the screen.
* Visualization: Bounding boxes (rectangles) are drawn around the detected faces, eyes, and bodies for visual feedback. 

# Installation
1. Clone the repository
2. Install the necessary dependencies
3. Ensure that OpenCV, numPy is installed
4. Download the Haar Cascade Classifier XML files from OpenCV's GitHub repository
5. Make sure that the Face Haarcascade Classifier is in the same location as in the Eye Haar Cascade.
6. Load the face and eye classifiers using CascadeClassifiers.

### Load the Haarcascade classifiers
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
* Facial and Eye Detection: The program efficiently detects faces and eyes in images and video frames, drawing bounding boxes around the detected features for easy visualization.
* Real-Time Detection: The webcam functionality allows for real-time face, eye, and body detection, with rectangles drawn around detected objects.

# Result of Facial and Eye detection in a JPG file
![WhatsApp Image 2024-09-22 at 20 32 39_2a34dd77](https://github.com/user-attachments/assets/7b8f45d7-8486-446e-8225-9ce3f6d5478c)

# Result of real-time face & eye detection through a webcam.
![WhatsApp Image 2024-09-22 at 20 32 39_40ccffce](https://github.com/user-attachments/assets/821884d7-b921-457e-86ee-28c957b393e0)

# Result of Facial and Eye detection in a Video file
![WhatsApp Image 2024-09-22 at 20 32 42_3598c91a](https://github.com/user-attachments/assets/990dec7e-c61a-4706-be40-1c2ceaebde72)


# Detection of human bodies in a video stream
![WhatsApp Image 2024-09-22 at 20 32 39_fa234c8d](https://github.com/user-attachments/assets/98b329c8-33ce-45b4-b0a5-7c3b0a192ead)


