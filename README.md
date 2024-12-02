# Real-Time Object Detection using YOLOv9

   This project demonstrates real-time object detection using the YOLOv9 model, implemented in Python with PyTorch. The model detects various objects in video frames captured from the webcam, draws bounding boxes, and displays class labels with confidence scores.

## Requirements

   - Python 3.x
   - PyTorch
   - OpenCV
   - Ultralytics YOLO

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/real-time-object-detection.git
   cd real-time-object-detection
   
2. Install the required dependencies:
   - pip install -r requirements.txt
   - pip install torch opencv-python ultralytics

## Setup
  - Download the YOLOv9 model weights (e.g., yolov9c.pt) and place them in the project directory.
  - Make sure that you have a working camera connected to your device.

## Model Description
   - YOLOv9 is a state-of-the-art object detection model that can detect various objects in images and videos. The model is used here for detecting and classifying objects in video frames captured from the webcam.


## License
   - This project is open-source and available under the MIT License.

---

## Features
  - Real-time object detection with a webcam feed.
  - Bounding boxes with class labels and confidence scores displayed on the video frames.
  - Press q to exit the application.
## Requirements
  - Python 3.8 or higher
  - GPU with CUDA support (Optional but recommended)
  - Required Python Libraries:
      - torch
      - opencv-python
      - ultralytics
## How It Works
  - Model Loading: The YOLOv9 model is loaded and moved to the appropriate device (GPU or CPU).
  - Video Capture: OpenCV is used to capture frames from the webcam.
  - Object Detection: Each frame is passed through the YOLO model for inference.
  - Results Visualization: Detected objects are highlighted with bounding boxes and labeled with their class and confidence.
## Acknowledgments
  - Ultralytics for the YOLOv9 implementation.
  - OpenCV for video processing.
## Structure
```bash
real-time-object-detection/
│
├── models/                     # Directory to store YOLO model weights
│   └── yolov9c.pt              # YOLOv9 model weights file
│
├── src/                        # Source code directory
│   └── main.py                 # Main Python script for real-time object detection
│
├── requirements.txt            # List of project dependencies
├── README.md                   # Documentation for the project
├── .gitignore                  # Git ignore file
└── LICENSE                     # License for the project (optional)
```


### **requirements.txt** (if you don't have it already):

   ```txt
   torch
   opencv-python
   ultralytics
