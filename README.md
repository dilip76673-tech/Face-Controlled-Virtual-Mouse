
# AI Head & Eye Controlled Virtual Mouse

This project is a Computer Vision based virtual mouse system that allows users to control the mouse cursor using head movement and eye gestures.

## 🚀 Features

- Head movement controls mouse cursor
- Eye blink for mouse click
- Wide eye gesture for scroll up
- Slight eye close for scroll down
- Automatic eye size calibration
- Smooth cursor movement
- Real-time face tracking using MediaPipe

## 🧠 Technologies Used

- Python
- OpenCV
- MediaPipe Face Mesh
- PyAutoGUI
- NumPy

## ⚙️ How It Works

1. The system tracks facial landmarks using MediaPipe.
2. Nose landmark is used to track head movement.
3. Eye aspect ratio (EAR) is calculated to detect:
   - Blink (click)
   - Wide eye (scroll up)
   - Slight eye close (scroll down)
4. Cursor movement is smoothed for stability.

## 📦 Installation

```bash
pip install opencv-python mediapipe pyautogui numpy

