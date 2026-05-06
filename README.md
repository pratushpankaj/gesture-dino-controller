# gesture-dino-controller
Control the Chrome Dino game using real-time hand gestures with OpenCV, MediaPipe, and PyAutoGUI. One finger to jump, two fingers to duck.
# 🎮 Gesture Dino Controller

Control the Chrome Dino game using your hand gestures 🤚
Built using **OpenCV**, **MediaPipe**, and **PyAutoGUI**

---

## 🚀 Features

* 👆 1 Finger → Jump
* ✌️ 2 Fingers → Duck (Hold Down Key)
* 🖐️ No Gesture → Release Key
* 📷 Real-time hand tracking using webcam

---

## 🧠 How It Works

* Uses **MediaPipe** to detect hand landmarks
* Counts number of fingers
* Maps gestures to keyboard actions using **PyAutoGUI**
* Controls the Chrome Dino game in real time

---

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe
* PyAutoGUI

---

## ▶️ Usage

1. Run the script:

```bash
python game_controller.py
```

2. Open Chrome Dino Game
   👉 Go to: `chrome://dino`

3. Use your hand:

* ☝️ One finger → Jump
* ✌️ Two fingers → Duck

---

## ⚠️ Requirements

* Webcam required
* Good lighting for better detection
* Keep hand visible in camera

---
## Coder
PRATYUSH PANKAJ
