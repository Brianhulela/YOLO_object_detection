# YOLO Object Detection with Ultralytics

## Overview
This notebook demonstrates how to perform object detection using the Ultralytics YOLO11 model. It covers detection on both images and videos, along with visualization of the annotated results inside a Jupyter Notebook.

## Contents
- **Environment Setup** – Installing and importing required libraries.  
- **Model Loading** – Using a pretrained YOLO11 model.  
- **Image Detection** – Running predictions on a sample image and displaying results.  
- **Video Detection** – Running predictions on a video file and saving annotated output.  
- **Bounding Box Data** – Accessing detection coordinates, class names, and confidence scores.  

## Notes
- Pretrained YOLO models are limited to common object classes.  
- For detecting custom objects, the model can be fine-tuned on a custom dataset.  
- Example use case: fine-tuning YOLO11 for medical image detection such as kidney stones.  
