# Real-Time Object Detection and Tracking

## Project Description
This project detects and tracks objects in real time using a webcam. It uses YOLO for object detection and Deep SORT for object tracking.

## Features
- Real-time webcam video capture.
- Object detection using YOLO.
- Bounding boxes around detected objects.
- Object classification with labels.
- Object tracking using Deep SORT.
- Unique tracking IDs for detected objects.

## Technologies Used
- Python 3.12
- OpenCV
- YOLO (Ultralytics)
- Deep SORT
- NumPy

## Installation

1. Clone or download this repository.
2. Open the project folder.
3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate the environment on Windows:

```bash
venv\Scripts\activate
```

5. Install the required packages:

```bash
pip install -r requirements.txt
```

## How to Run

Run the following command:

```bash
python object_detection.py
```

Show objects in front of your webcam. The application will detect objects and assign tracking IDs.

Press `Q` to close the application.

## Screenshots

Screenshots of object detection and tracking are available in the `screenshots` folder.

## Author
Prathiksha D

## Internship
CodeAlpha AI Internship