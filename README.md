#Hand Gesture Controlled Virtual Mouse

This project implements a hand gesture-controlled virtual mouse using computer vision and machine learning. The virtual mouse allows users to control the mouse pointer, click, and scroll using hand gestures captured through a webcam.

#Features

Mouse Movement: Control the mouse pointer by moving your hand.
Left Click: Perform a left click by pinching your thumb and index finger together.
Right Click: Perform a right click by bringing your thumb and middle finger together.
Scrolling: Scroll up or down by raising or lowering your middle finger.

#Technologies Used

Python: The primary programming language.
OpenCV: For image processing and capturing webcam input.
Mediapipe: For hand landmark detection and gesture recognition.
PyAutoGUI: To simulate mouse actions based on recognized gestures.

#Installation
Prerequisites
Python 3.7 or higher
A webcam for capturing video input

Installing the dependencies
"pip install opencv-python mediapipe pyautogui"

#Troubleshooting
DLL Load Failures: Ensure that the Microsoft Visual C++ Redistributable is installed.
Incorrect Mouse Movements: Adjust the camera angle or ensure that the lighting is adequate for gesture detection.
