# Eye Mouse Control

This project enables mouse control using eye movements. It uses a webcam to track specific points on the face, specifically around the eyes, and translates those movements into mouse cursor movement. It also allows clicking when a certain eye gesture is detected.

## Features

- **Mouse Cursor Control**: Move the mouse cursor using the eye movement detected through the webcam.
- **Clicking Gesture**: Detects a specific eye gesture (blinking) to simulate mouse clicks.
- **Face Mesh for Eye Tracking**: Uses the `MediaPipe` Face Mesh model to detect facial landmarks, specifically around the eyes, for precise tracking.
- **Real-time Display**: Shows the live webcam feed with visual markers for tracking eye landmarks.

## Requirements

- Python 3.x
- Libraries:
  - `pyautogui`: For controlling the mouse and simulating clicks.
  - `opencv-python`: For video capture and image processing.
  - `mediapipe`: For facial landmark detection.
  
You can install the required libraries using:

```bash
pip install pyautogui opencv-python mediapipe
