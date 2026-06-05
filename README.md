# Vehicle Detection System using YOLOv9

## Overview

This project implements a Vehicle Detection System using the YOLOv9 object detection model. The system can detect vehicles in images and videos in real time with high accuracy.

## Features

- Real-time vehicle detection
- Video processing support
- High detection accuracy
- YOLOv9-based model
- OpenCV integration

## Technologies Used

- Python
- YOLOv9
- OpenCV
- PyTorch
- NumPy

## Dataset

Dataset Download Link:
https://drive.google.com/file/d/133lVDSEvaKtR9Yxuua9xdXNwY6Si6oWR/view?usp=drive_link

## Installation

```bash
git clone https://github.com/yourusername/Vehicle-Detection-System.git

cd Vehicle-Detection-System

pip install -r requirements.txt
```

## Training

```bash
yolo detect train data=data.yaml model=yolov9c.pt epochs=50
```

## Testing

```bash
python detect.py
```

## Results

The trained model successfully detects vehicles in real-time traffic videos and images.

## Future Scope

- Vehicle counting
- Speed estimation
- Traffic density analysis
- Smart city applications

## Results

![Detection 1](Screenshot%202026-05-14%20230733.png)

![Detection 2](Screenshot%202026-05-14%20230803.png)

![Detection 3](Screenshot%202026-05-14%20230831.png)
