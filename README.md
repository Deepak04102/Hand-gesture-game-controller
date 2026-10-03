 🎮 Hand Gesture Game Controller

A Computer Vision project that enables game controls using hand gestures. The application tracks the index finger in real time through a webcam and converts swipe gestures into keyboard arrow key inputs, allowing touchless interaction with games and applications.

---

 📌 Overview

Hand Gesture Game Controller is a real-time computer vision application that uses MediaPipe Hand Tracking and OpenCV to recognize index finger swipe gestures. The detected gestures are mapped to keyboard arrow keys using PyAutoGUI, enabling users to control games or navigate applications without touching the keyboard.

---

 ✨ Features

- ✋ Real-time hand tracking
- 👆 Index finger swipe detection
- ⬅️➡️ Left and Right arrow key control
- ⬆️⬇️ Up and Down arrow key control
- 🎮 Touchless game interaction
- 📷 Live webcam-based gesture recognition
- ⚡ Smooth real-time performance

---

 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI

---

 📂 Project Structure

```text
Hand-Gesture-Game-Controller/
│
├── handgame.py
├── README.md
└── requirements.txt
```


 ▶️ How It Works

1. Access the webcam.
2. Detect the user's hand using MediaPipe.
3. Track the index finger position.
4. Identify swipe direction.
5. Convert the detected gesture into keyboard arrow key inputs.
6. Control games or applications using hand gestures.

---

 🎮 Gesture Controls

| Hand Gesture | Keyboard Action |
|--------------|-----------------|
| Swipe Left | Left Arrow Key |
| Swipe Right | Right Arrow Key |
| Swipe Up | Up Arrow Key |
| Swipe Down | Down Arrow Key |

---

 📸 Sample Output

The application displays the webcam feed with hand landmarks while recognizing swipe gestures. Detected gestures are translated into keyboard arrow key inputs in real time.

---

