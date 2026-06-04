# Physics-Informed IoT-Based Drone Detection System

## Overview
Developed a real-time drone detection system using YOLOv8, OpenCV, ESP32, and Telegram API. The system detects drones from video streams and generates automated alerts for monitoring and surveillance.

## Technologies Used
- Python
- YOLOv8
- OpenCV
- ESP32
- Telegram API

## Key Features
- Real-time drone detection using YOLOv8
- Distinction between drones and birds
- Physics-informed filtering using trajectory, speed, acceleration, and stability analysis
- IoT-based alert generation through ESP32
- Telegram notification system
- Performance evaluation on real-world drone videos and custom datasets

## My Contribution
This project was completed by a team of two members.

My contribution:
- Dataset collection and preprocessing
- YOLOv8 model training and testing
- Model evaluation and performance analysis

Teammate contribution:
- ESP32 integration
- Telegram alert system
- IoT implementation

## Repository Contents
- Yolo_Training.ipynb
- train_results/
- Project documentation

## Results
The system was evaluated on 10+ real-world drone videos and custom datasets. Training results, confusion matrix, precision, recall, and F1-score graphs are included in the repository.

## Note
The trained model weight files (best.pt and last.pt) are not included due to GitHub file size limitations.
