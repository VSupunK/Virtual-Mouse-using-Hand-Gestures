# Virtual Mouse Using OpenCV

In this project, I utilize the live feed from the webcam to create a virtual mouse using hand tracking.

## Project Description
In this project, I am using my hand as a virtual mouse that can perform all the functions of a physical mouse without touching the system. By detecting my hands via the webcam, a bounding box is created around my hand, focusing on two fingers: the index finger and the thumb. The index finger acts as a cursor, and moving it around moves the cursor on the screen. To simulate a mouse click, the system detects the distance between the thumb and the index finger. When they are brought close together, a click is performed.

Additionally, a smoothness factor is implemented to address the shakiness of the movement.

## Requirements
The following modules need to be installed for the project to work properly:

1. **OpenCV:**
   - OpenCV is an open-source library for computer vision, machine learning, and image processing. It supports various programming languages like Python, C++, Java, etc. It can process images and videos to identify objects, faces, or even handwriting.
   - Installation: `pip install opencv-python`

2. **Mediapipe:**
   - MediaPipe is a framework for building multimodal (e.g., video, audio, any time series data), cross-platform (i.e., Android, iOS, web, edge devices) applied ML pipelines.
   - Installation: `pip install mediapipe`

3. **PyAutoGUI:**
   - PyAutoGUI is a cross-platform GUI automation Python module for programmatically controlling the mouse and keyboard.
   - Installation: `pip install pyautogui`

## Important Note
To ensure the project runs smoothly, Python 3.11.6 is used for this implementation.
