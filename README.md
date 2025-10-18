# Face Detection with YOLOv8

> Real-time, high-accuracy face detection using a fine-tuned YOLOv8 model.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-000000?style=for-the-badge&logo=ultralytics&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

## Project Overview

This project implements a real-time face detection system using YOLOv8, a state-of-the-art object detection architecture. The model is fine-tuned on diverse face datasets to ensure robust performance across varying lighting conditions, poses, and partial occlusions—making it ideal for applications like attendance systems, security, and user authentication.

### Features
- Pre-trained YOLOv8 model fine-tuned for face detection  
- Fast inference suitable for real-time applications  
- High accuracy on various lighting conditions, poses, and partial occlusions  
- Lightweight and efficient (based on YOLOv8n architecture)  
- Easy to integrate into images, videos, or live camera streams

## Dataset & Model

- **Base Model**: YOLOv8n from [yolov8-face](https://github.com/lindevs/yolov8-face)  
- **Training Data**: Aggregated from public face datasets (e.g., WIDER FACE) with augmentations  
- **Output**: Bounding boxes around detected faces with confidence scores  

## Performance Metrics

| Metric        | Value                          |
|-------------|----------------------------------|
| Precision      | 0.95 |
| Recall     | 0.95 |
| mAP@0.5 | 0.98 |
| mAP@0.5:0.95      | 0.88 |

<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/f4b3ab00-fbfc-49d1-b0cd-5a6a0a8edfd8" />

