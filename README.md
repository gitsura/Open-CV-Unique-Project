# Open-CV-Unique-Project
# Hand Gesture-Based PowerPoint Controller

## About the Project
This project allows users to control PowerPoint slides using hand movements in front of a laptop webcam.

It uses OpenCV to detect hand movements and PyAutoGUI to move between slides.

## Technologies Used
- Python
- OpenCV
- NumPy
- PyAutoGUI
- Jupyter Notebook

## Features
- Detects hand movements using a webcam.
- Swipe right to move to the next slide.
- Swipe left to move to the previous slide.
- Touchless presentation control.

## Installation

```bash
pip install opencv-python numpy pyautogui
```

## How to Run
1. Open Jupyter Notebook.
2. Run the Python code.
3. Open PowerPoint and start the slideshow using F5.
4. Show your hand in front of the webcam.
5. Swipe right or left to control slides.
6. Press Q to close the webcam window.

## Working
1. Captures video using the webcam.
2. Detects skin-colored regions using HSV.
3. Finds contours using OpenCV.
4. Tracks hand movement using centroid calculation.
5. Detects left and right swipe gestures.
6. Uses PyAutoGUI to control PowerPoint.

## Applications
- Classroom presentations.
- Business meetings.
- Online teaching.

## Author
Sura Varsha
