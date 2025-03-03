# YOLO Object Detection Project

This project is a **Streamlit-based web application** for object detection using **YOLOv3, YOLOv5, and YOLOv8**. Users can upload images, select a model, and view detection results with **pre-trained weights and adjustable confidence thresholds**.

## Features
- Supports **YOLOv3, YOLOv5, and YOLOv8** models
- Upload an image and perform object detection
- Interactive UI with **Streamlit**
- Adjustable confidence thresholds
- Real-time processing with **pre-trained YOLO weights**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/yolo-object-detection.git
   cd yolo-object-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the required YOLO weights and place them in the project directory.

## Usage
Run the Streamlit app:
```bash
streamlit run Sourcecode.py
```

## Requirements
- Python 3.x
- OpenCV
- NumPy
- PIL
- Streamlit
- PyTorch
- Ultralytics YOLO

## Model Selection
- **YOLOv3**: Uses OpenCV’s DNN module for detection.
- **YOLOv5**: Uses PyTorch-based model from the Ultralytics repository.
- **YOLOv8**: Uses the latest Ultralytics YOLO model.



