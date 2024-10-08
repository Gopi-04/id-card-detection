# YOLO Object Detection for ID Card

## Overview

This project demonstrates an application of YOLO (You Only Look Once) for real-time object detection and distance measurement of ID cards using a webcam. The application utilizes a pre-trained YOLO model to detect ID cards, draw bounding boxes around detected objects, and calculate the distance from the camera based on the size of the detected object.

## Features

- **Real-Time Object Detection:** Uses the YOLO model to detect ID cards in real-time from a webcam feed.
- **Bounding Boxes:** Draws bounding boxes around detected ID cards with confidence scores.
- **Distance Calculation:** Computes the approximate distance of the ID card from the camera based on the size of the detected object.
- **Dynamic Labels:** Displays confidence percentage and distance information on the video feed.
- **Customizable Thresholds:** Allows adjustment of confidence thresholds for detection accuracy.

## Technologies Used

- **Python:** Programming language used for scripting.
- **Ultralytics YOLO:** YOLO model for object detection.
- **OpenCV:** Library for image processing and video capture.

## Getting Started

To get started with this project, follow these steps:

### Clone the Repository

```bash
git clone https://github.com/Gopi-04/id-card-detection.git
```

### Install Dependencies

Ensure you have the required libraries installed. You can install them using pip:

```bash
pip install ultralytics opencv-python numpy
```

### Download YOLO Model

Download the pre-trained YOLO model (`id_card_v5.pt`) from the provided source or train your own model and place it in the project directory.

### Run the Script

Execute the script using Python:

```bash
python id_card_v5.pt
```

### View Results

The webcam feed will open in a window displaying detected ID cards, bounding boxes, confidence scores, and calculated distances.

# Contact

For any questions or feedback, please contact me at [pvgopi04@gmail.com](mailto:pvgopi04@gmail.com).
