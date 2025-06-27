# 👁️ EyePilot: Eye-Controlled Mouse Cursor & Scrolling System

EyePilot is a hands-free, AI-powered system that enables users to control their mouse cursor and perform scrolling using only eye movements. This system leverages facial landmark detection and gaze tracking to provide a touchless, accessible, and intuitive interface — ideal for assistive technologies and Human-Computer Interaction (HCI) research.

---

 📸 Demo Preview

![Demo GIF](demo.gif) <!-- Add a demo gif if available -->

---

 🚀 Features

- 🎯 Real-time mouse movement using eye direction
- 🖱️ Scroll control (up/down) through gaze positioning
- 📷 Webcam-based tracking with no additional hardware required
- 🧠 Face & eye detection using dlib’s 68-point shape predictor
- 🖥️ PyAutoGUI for seamless system-level cursor and scroll actions
- ♿ Designed with accessibility and hands-free computing in mind

---

🧰 Technologies Used

- Python 3.10+
- [OpenCV](https://opencv.org/) for video processing
- [dlib](http://dlib.net/) for facial landmark detection
- [PyAutoGUI](https://pyautogui.readthedocs.io/) for cursor and scroll simulation

---

📦 Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/eye-pilot.git
cd eye-pilot

2. Install dependencies

```bash
pip install -r requirements.txt

3. Download model files

shape_predictor_68_face_landmarks.dat (extract .dat file from .bz2)

haarcascade_eye.xml (right-click > Save As > XML)

📂 Place both files in the project root directory.

📁 Project Structure

eye-pilot/
│
├── eye_cursor.py                  # Main script
├── shape_predictor_68_face_landmarks.dat  # Dlib model file
├── haarcascade_eye.xml            # Haar cascade for eye detection
├── requirements.txt
└── README.md

⚠️ Notes
Works best in bright lighting conditions

Cursor movement depends on head stability and eye visibility

Tested on Windows 10/11 with Python 3.10+

🤝 Contributing
Contributions are welcome! To contribute:

Fork this repo

Create a new branch (git checkout -b feature-name)

Commit your changes

Push and open a pull request

📜 License
This project is licensed under the MIT License.

🙋‍♀️ Acknowledgements
dlib

OpenCV

PyAutoGUI

OpenCV Haar Cascade Classifiers




