# 🖱️ AI-Powered Virtual Mouse using MediaPipe & Python

An **AI-based Virtual Mouse system** that allows users to control the mouse cursor and perform click actions using **hand gestures**, powered by **MediaPipe**, **OpenCV**, and **Python** — all through a webcam.

This project demonstrates **real-time computer vision**, **gesture recognition**, and **human-computer interaction**, enabling a fully touchless mouse experience.

---

## 🚀 Features

- 🎥 Real-time hand tracking using **MediaPipe Hands**
- 🖱️ Smooth cursor movement using index finger
- 👆 Gesture-based left-click detection (index + middle finger)
- 📐 Active region mapping to reduce cursor glitches
- ⚡ FPS monitoring for performance analysis
- 🤖 Touchless and hardware-free interaction

---

## 🧠 How It Works

1. Webcam captures live video frames
2. MediaPipe detects **21 hand landmarks**
3. Index finger position is mapped to screen coordinates
4. Cursor movement is smoothed for better control
5. Distance between index & middle fingers triggers a click
6. Active region limits sudden jumps and glitches

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **MediaPipe**
- **PyAutoGUI**
- **NumPy**

---

## 📂 Project Structure

```text
Virtual-Mouse/
│
├── virtual_mouse.py        # Main Python script
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
