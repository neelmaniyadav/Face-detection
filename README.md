# Face Detection System

## Overview
This is a **real-time face detection system** using OpenCV in Python. It captures video from the webcam, detects human faces using a Haar Cascade classifier, and displays them with bounding boxes.

## Features
- Real-time face detection using OpenCV.
- Uses `haarcascade_frontalface_default.xml` for detecting faces.
- Draws a bounding box around detected faces.
- Stops execution when the **down arrow key (↓)** is pressed.

## Requirements
Ensure you have the following installed:
- Python 3.x
- OpenCV (`cv2` module)

Install OpenCV using:
```bash
pip install opencv-python
