# Hand Gesture Control System 🎮🖐️

A real-time Python project that uses **OpenCV**, **MediaPipe**, **PyAutoGUI**, and **Pycaw** to detect hand gestures from a webcam feed and perform actions such as:

- ✅ Volume control  
- 🖱️ Mouse cursor movement & click  
- 🔃 Scroll up/down  
- 🪞 **Mirrored camera view** for a natural feel

---

## 📸 Demo

![Demo GIF or Screenshot Here](#)  
> *(Add your own GIF/image showing hand gestures in action)*

---

## 🔧 Features

- 🔍 Real-time hand tracking using MediaPipe
- 🎚️ Smooth system volume control with finger distance
- 🖱️ Move cursor with your index finger (with smoothing)
- 🔘 Left-click using thumb-finger gesture
- 🔘 Right-click using pinky-palm gesture
- 📜 Scroll based on two-finger movement
- 🪞 Mirrored video feed for intuitive interaction

---

## 🧠 Tech Stack

- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [MediaPipe](https://google.github.io/mediapipe/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)
- [Pycaw](https://github.com/AndreMiras/pycaw)

---

## 📁 Project Structure
```
📦 HandGestureControl
│
├── HandTrackingModule.py  # Hand detection using MediaPipe
├── main.py                # Main application
└── README.md              # Project documentation
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/HandGestureControl.git
cd HandGestureControl
```
### 2. Install Dependencies
```python
pip install opencv-python mediapipe numpy pyautogui comtypes pycaw
```
🔐 For Windows: Make sure your Python is 64-bit and you have microphone/speaker drivers for pycaw.