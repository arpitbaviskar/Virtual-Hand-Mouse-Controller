# Virtual-Hand-Mouse-Controller
Control your computer’s cursor using just your hand gestures! This Python project uses OpenCV, Mediapipe, and PyAutoGUI to create a real-time virtual mouse that detects hand landmarks via your webcam and performs mouse movements and clicks.
The Virtual Hand Mouse Controller lets you control your computer’s mouse using your hand gestures through your webcam — no hardware required! It leverages OpenCV for real-time video capture, Mediapipe for hand tracking, and PyAutoGUI for controlling the cursor movements and clicks.

✨ Features
Real-time hand tracking using Mediapipe Hands API

Move the cursor by moving your index finger

Perform a click when your index finger and thumb meet

Works entirely with your webcam — no special sensors needed

🧩 Tech Stack
Python 3.x

OpenCV – video streaming and frame processing

Mediapipe – hand landmark detection

PyAutoGUI – screen control automation

⚙️ Installation
Clone this repository:

bash
git clone https://github.com/yourusername/virtual-hand-mouse.git
cd virtual-hand-mouse
Install dependencies:

bash
pip install opencv-python mediapipe pyautogui
Run the project:

bash
python virtual_mouse.py
🧠 How It Works
The webcam captures a live video feed using OpenCV.

Mediapipe detects 21 landmarks on your hand.

The coordinates of the index finger tip (landmark 8) are mapped to your screen’s resolution for controlling your cursor.

When your thumb tip (landmark 4) comes close to your index finger, a click event is triggered.

🖼️ Example Usage
Raise your hand in front of the webcam.

Move your index finger around to move the cursor.

Bring your thumb close to your index finger to click.

🚀 Future Enhancements
Add gesture recognition for double-click, drag, or scroll.

Implement multi-hand support.

Enhance stability with smoothing or Kalman filtering.

🤝 Contributing
Pull requests are welcome! If you have feature ideas, feel free to open an issue.

🪪 License
This project is licensed under the MIT License.

