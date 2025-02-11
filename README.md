YOLO-Based Car Number Plate Detection

Overview

This project implements a car number plate detection system using the YOLO (You Only Look Once) object detection algorithm. The system detects and extracts license plate numbers from images and video streams, providing real-time processing capabilities.

Features

Real-time license plate detection

High accuracy and speed using YOLO

Supports images and video streams

Option to integrate OCR for extracting text from detected plates

Technologies Used

YOLOv5/YOLOv8 (for object detection)

OpenCV (for image processing)

Python (primary programming language)

Installation

Prerequisites

Ensure you have Python installed (preferably 3.8+). Install the required dependencies using:

pip install -r requirements.txt

Clone the Repository

git clone https://github.com/your-repo/yolo-car-plate-detection.git
cd yolo-car-plate-detection

Running YOLO Detection

For image input:

python detect.py --source image.jpg --weights best.pt --conf 0.5

For video input:

python detect.py --source video.mp4 --weights best.pt --conf 0.5

Model Training

If you want to train YOLO on a custom dataset:

python train.py --img 640 --batch 16 --epochs 50 --data dataset.yaml --weights yolov5s.pt

Future Enhancements

Improve OCR accuracy for better text extraction

Deploy the application on cloud platforms

Add support for multi-camera input

Author

Karuna Kurewad

