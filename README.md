# DriveAware

**DriveAware** is a computer vision-based application that monitors driver alertness by analyzing facial cues such as eye closure and blink patterns. Built with OpenCV, it operates in real-time to trigger alerts when signs of drowsiness are detected.

---

## Features

* Real-time processing via webcam video stream
* Eye-status detection using facial landmarks
* Alerts to notify driver upon detection of drowsiness (sound or visual cues)
* Modular structure for easy maintenance and extension

---

## Tech Stack

* **Language**: Python
* **Data Handling**: NumPy
* **Algorithms**: Haar Cascades or Landmark-based detection for eye tracking

---

## Installation & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/DriveAware.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Start the application:

   ```bash
   python main.py
   ```
4. A webcam window will open and monitor for signs of drowsiness in real-time.

---



