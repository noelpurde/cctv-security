# Home Security Camera Using Python

This project uses Python to build a simple home security camera that can detect movement and trigger an alert when activity is detected. The idea was to create a low-cost movement detector as a Python project.

## Features
- Detects movement using a video stream.
- Highlights moving objects with bounding boxes.
- Plays an alert sound when motion is detected.

## Setup & Installation

To run this project, you will need the following Python libraries:

- **OpenCV** (`opencv-python`): Used for image processing, motion detection, and video stream handling.
- **winsound**: Used to play an alert sound when motion is detected (Windows only).  
  If you're using macOS or Linux, replace `winsound` with a cross-platform library like `playsound`.

### Install dependencies:
```bash
pip install opencv-python winsound
```

