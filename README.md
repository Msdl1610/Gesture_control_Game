# Gesture_control_Game
# Gesture Control for Subway Surfers 🖐🎮

This project allows you to play the **Subway Surfers** web game using just your **hand gestures** via a webcam — no keyboard or mouse needed!

## 🔧 Features

- Real-time **hand tracking** using [MediaPipe]
- Gesture-based controls to simulate:
  - 🔼 Jump (Swipe Up)
  - 🔽 Slide (Swipe Down)
  - ◀️ Move Left (Swipe Left)
  - ▶️ Move Right (Swipe Right)
- Auto-launches the game in your browser

## 📸 How It Works

1. Uses `cv2` to capture live webcam video.
2. `mediapipe` tracks the index fingertip’s position.
3. Calculates fingertip **velocity** to detect swipe gestures.
4. Uses `pyautogui` to simulate keyboard inputs (arrow keys).

## 🧰 Tech Stack
- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- Webbrowser module
