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
### 3. Run the App
```python
python main.py
```
## 🎮 Controls & Gestures

Use the following gestures to control various system functions. The camera view is mirrored for a natural, intuitive experience!

| Gesture                         | Action                           |
|----------------------------------|----------------------------------|
| ✊ (Fist)                        | Neutral Mode / Reset             |
| ☝️ (Index Finger Only)           | Scroll Mode                      |
| ✌️ (Index + Middle Fingers)      | Scroll Up/Down                   |
| 👍 + ☝️ (Thumb + Index)          | Volume Control                   |
| 🖐️ (All Fingers Open)           | Cursor Mode                      |
| 👉 (Index Finger)                | Move Mouse Cursor                |
| 🤏 (Thumb Near Palm)             | Left Click                       |
| 👋 (Pinky Near Palm)             | Right Click                      |

### 🖱️ Cursor Mode:

In **Cursor Mode**, move your mouse cursor by positioning your index finger. The cursor follows your finger's movement on the screen.

### 🔊 Volume Control:

To adjust the volume, bring your thumb and index finger close together or move them apart. The distance between the two fingers is mapped to system volume, allowing you to increase or decrease the sound.

### 🔃 Scroll:

Use the **Index + Middle Fingers** to scroll up or down. Position the two fingers vertically on the screen, and the direction of their movement will trigger scrolling.

### 🖱️ Mouse Clicks:

- **Left Click:** Bring your thumb close to your palm to simulate a left mouse click.
- **Right Click:** Bring your pinky close to your palm to simulate a right mouse click.

---

Let me know if you'd like to add more details or modify any gestures!
