# cctv-camara-motion-video
A Python-based CCTV motion detection system that automatically records video when movement is detected.

🛠️ Requirements & Installation

To run this CCTV motion detection and video recording project, make sure the following are installed:
1️⃣ Python
Python 3.7 or higher
python --version
Download Python: https://www.python.org

2️⃣ Required Python Libraries
Install the required packages using pip:
pip install opencv-python numpy
> Libraries used:
OpenCV (cv2) – camera access, motion detection, video recording
NumPy – image processing support

3️⃣ Camera Requirement
Built-in webcam or
External USB CCTV / USB camera
⚠️ The program will not run without a camera.

4️⃣ Supported Operating Systems
Windows
Linux
macOS

▶️ How to Run
python main.py

⏱️ Motion Logic
Recording starts automatically when motion is detected
If no motion is detected for 2 seconds, the video recording automatically stops

