This project is a real-time hand gesture control system built using Python, OpenCV, and MediaPipe.
It is optimized for Dell Latitude 5490 (Intel 8th Gen, 720p webcam).

The system allows you to control your computer using hand gestures.

Features

Control mouse using index finger

Click using pinch gesture (thumb + index)

Control presentation slides

Control volume

Play / Pause media

Switch windows

Toggle resolution (720p / 480p)

Real-time FPS display

Supported Gestures
Gesture	Action
Index finger up	Move mouse
Pinch (thumb + index)	Mouse click
Thumbs up	Next slide / Volume up
Fist	Previous slide / Volume down
Open hand	Play / Pause
Peace sign	Switch windows
Technologies Used

Python

OpenCV

MediaPipe

NumPy

PyAutoGUI

Psutil

 Installation

Install required packages:

pip install opencv-python mediapipe pyautogui numpy psutil


If using Windows model detection:

pip install wmi

How to Run
python latitude_5490_gesture.py

Keyboard Controls
Key	Function
M	Mouse mode
G	Gesture mode
P	Presentation mode
V	Media mode
R	Change resolution
C	Calibrate webcam
B	Change brightness
Q	Quit program
Tips for Best Performance

Use good lighting

Keep hand 30–60 cm from camera

Use plain background

Avoid strong backlight

If webcam doesn’t work → Press FN + F10

Output Shows

FPS (Frames per second)

Current mode

Detected gesture

Action performed

Author

Varshini S
