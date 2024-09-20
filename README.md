# Red Rectangle Detection

This project detects red rectangles in video streams using OpenCV. It applies color thresholding in the HSV color space and utilizes contour detection to identify and draw bounding boxes around red rectangles in real-time.

## Features

- Real-time video capture from the webcam.
- Detection of red rectangles using color thresholding.
- Drawing bounding boxes around detected rectangles.
- Displaying frames with FPS information.

## Requirements

- Python 3.x
- OpenCV
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alperenpy/red-rectangle-detection-with-openCV.git
2. Install required Python libraries:
   ```bash
   pip install opencv-python numpy

## Usage

1. Run the script to start detecting red rectangles:
   ```bash
   python red_rectangle_detection.py
2. Press q to exit the detection loop.
