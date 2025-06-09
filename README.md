# MediaPipe-Hand-Tracking-Webcam
This project implements real-time hand tracking using MediaPipe and Opencv. It uses your webcam to detect and track 21 key hand landmarks, useful for gesture recognition, control systems, and interactive applications.
## Features
- Real-time hand tracking from webcam
- Detects 21 hand landmarks per hand
- Supports single or multiple hands
- High accuracy and low latency
- Built using MediaPipe and Opencv
## Requirements
Install the required libraries using pip:
pip install mediapipe opencv-python
## How It Works
- MediaPipe Hands detects palms and extract 21 key landmarks per hand.
- Opencv handles webcam input and drawing visualizations.
- You can extend this base to recognize gestures, control systems, or games.
