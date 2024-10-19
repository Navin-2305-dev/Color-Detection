# Colour Detection with OpenCV

This Python project detects a specific color from a webcam using OpenCV and highlights the detected color area by drawing a bounding box around it. The color in focus here is **yellow**, but it can be easily modified to detect other colors.

## Features

- Real-time color detection using the HSV color space.
- Bounding box generation around the detected color area.
- Adjustable color limits for different hues.
  
## Prerequisites

Before running the project, make sure you have the following Packages installed:

- OpenCV (`cv2`)
- PIL (`Pillow`)
- NumPy

To install the dependencies, run:

```bash
pip install opencv-python pillow numpy
