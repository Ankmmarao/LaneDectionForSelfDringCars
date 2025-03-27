# Lane & Vehicle Detection System

A Flask-based video processing system using YOLOv3 for vehicle detection and lane detection with safety suggestions.

## Features
- Video upload and processing
- Real-time lane detection
- Vehicle detection and distance estimation
- Safety suggestions and warnings
- Speed estimation using optical flow

## Installation
1. Clone repository:
```bash
git clone https://github.com/yourusername/lane-vehicle-detection.git
cd lane-vehicle-detection


wget https://pjreddie.com/media/files/yolov3.weights -P yolov3/
wget https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg?raw=true -O yolov3/yolov3.cfg
wget https://github.com/pjreddie/darknet/blob/master/data/coco.names?raw=true -O yolov3/coco.names
