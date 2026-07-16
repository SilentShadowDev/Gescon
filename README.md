# Gescon ✋🖥️

> Control your computer naturally using hand gestures.

Gescon is a real-time hand gesture recognition system that transforms your webcam into a touchless input device. It enables users to control their computer using intuitive hand gestures for mouse movement, clicking, scrolling, screenshots, volume control, and more.

---

## ✨ Features

- 🖱️ Virtual Mouse Control
- 👆 Left Click
- 👉 Right Click
- ✌️ Double Click
- 🤏 Drag & Drop
- 📜 Smooth Scrolling
- 📸 Screenshot Capture
- 🔊 Volume Control
- 🎯 Real-time Hand Tracking
- ⚡ Low Latency Gesture Recognition

---

## 🛠️ Built With

- Python 3.11
- OpenCV
- MediaPipe 0.10.21
- PyAutoGUI 0.9.54
- NumPy 

---

## 📂 Project Structure

```
Gescon/
│
├── assets/
├── models/
├── utils/
├── main.py
├── requirements.txt
└── README.md
```

*(Folder names may vary depending on the project structure.)*

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/SilentShadowDev/Gescon.git
```

Move into the project

```bash
cd Gescon
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python main.py
```

---

## 🎮 Supported Gestures

| Gesture | Action |
|---------|--------|
| ☝️ Index Finger | Move Cursor |
| 🤏 Thumb + Index | Left Click |
| 🤏 Thumb + Middle | Right Click |
| ✌️ Two Finger Gesture | Double Click |
| 🤏 Pinch & Hold | Drag & Drop |
| ✋ Open Palm | Scroll Mode |
| 👍 Thumb + Pinky | Screenshot |
| 🤏 Thumb Distance | Volume Control |

> Gesture mappings can be customized in the source code.

---

## 📷 How It Works

1. Webcam captures live video.
2. MediaPipe detects hand landmarks.
3. Gestures are recognized using landmark positions.
4. Recognized gestures are mapped to system actions.
5. PyAutoGUI performs the corresponding mouse or keyboard operation.

---

## 📦 Requirements

- Python 3.10
- Webcam
- Windows / macOS / Linux

Install manually:

```bash
pip install opencv-python mediapipe pyautogui numpy
```

---

## 📈 Future Improvements

- Gesture customization GUI
- Multi-hand support
- Application-specific shortcuts
- AI-based gesture learning
- Voice + Gesture hybrid controls
- Cross-platform optimization

---

