# 🖐️ Hand Gesture Control: Audio & Brightness Adjuster

This project uses your **webcam and hand gestures** to control your **system volume** and **screen brightness** — without touching your keyboard or mouse. Built using **MediaPipe**, **OpenCV**, and **PyCAW**, 
it brings an intuitive, contactless control experience to your PC.

## 🚀 Features

- 🟢 **Control Volume** with your **left hand** (distance between thumb and index).
- 🟡 **Control Brightness** with your **right hand**.
- 🔴 Real-time hand tracking with landmarks using **MediaPipe**.
- 🎯 Smooth interaction using `cv2`, `numpy`, and interpolation.
- 💻 Designed for **Windows** systems (brightness & audio APIs).

## 📷 How It Works

- 📍 The webcam captures your hand.
- 📌 MediaPipe detects hand landmarks.
- 📏 The distance between your thumb and index finger is calculated.
- 🎚 Volume or brightness is adjusted based on which hand is raised and how far apart your fingers are.

## 📦 Requirements

Install all required libraries in your virtual environment or Anaconda:

In bash
pip install opencv-python mediapipe screen_brightness_control pycaw comtypes numpy


🙋‍♂️ Author
Muccharla Praveen

