# Vehicle Counting Using YOLO and Object Tracking

This project implements a vehicle counting system based on object detection and tracking. The goal is to count vehicles moving in two directions (upwards and downwards) from a video stream using the YOLO model and OpenCV.

## Overview
The system detects vehicles in each frame, tracks their movement across two reference lines, and counts them depending on their direction of travel.  
When the center of a detected vehicle crosses one line and then the other, the counter is updated accordingly.

## Key Features
- Vehicle detection using a pre-trained YOLO model  
- Object tracking with unique IDs for each detected vehicle  
- Counting vehicles moving **upwards** and **downwards**  
- Real-time visualization of bounding boxes, lines, and counts  

## Methods and Tools
- **Language:** Python  
- **Libraries:** `pandas`, `matplotlib`, `cv2`, `ultralytics`
- **Model:** YOLOv8s
