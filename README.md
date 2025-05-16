# 🍎🍌 Fruit Object Detection using YOLOv5

✌ Hello! This project is an object detection pipeline built using **YOLOv5** to detect and classify **8 types of fruits**. The model is trained on a custom dataset with the help of tools like **Roboflow** for dataset preparation and augmentation.

## ✨ Overview

This repository contains all the necessary code and configuration to train and run a YOLOv5 model for detecting fruits in images.

- 🔍 **Object Detection**: Localizes and classifies 8 fruit categories.
- ⚡ **YOLOv5**: A fast and accurate one-stage object detector.
- 🔧 **Roboflow**: Used for dataset conversion, augmentation, and annotation management.

## 🍇 Fruit Classes

The dataset includes the following 8 classes:

1. Apple  
2. Banana  
3. Orange  
4. Grapes  
5. Strawberry  
6. Pineapple  
7. Watermelon  
8. Mango

## 🛠️ Getting Started

### 1. Clone YOLOv5 repository

```bash
git clone https://github.com/ultralytics/yolov5.git
cd yolov5
pip install -r requirements.txt
