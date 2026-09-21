# YOLO License Plate Detection and Recognition

A computer vision project for **automatic license plate detection and recognition** using a custom-trained **YOLOv8s** object detection model combined with **OpenCV-based image processing** and **EasyOCR**.

The project detects license plates in vehicle images, refines the detected plate region using geometric features, preprocesses the cropped plate image, and attempts to recognize the license plate number using OCR.

---

## 📌 Project Overview

License plate detection is an important computer vision task used in applications such as:

- Automatic Number Plate Recognition (ANPR)
- Traffic monitoring
- Smart parking systems
- Vehicle identification
- Road surveillance
- Access-control systems
- Intelligent transportation systems

This project implements a complete pipeline:

```text
Input Vehicle Image
        ↓
YOLOv8 License Plate Detection
        ↓
Bounding Box Extraction
        ↓
Geometry-Based Bounding Box Refinement
        ↓
License Plate Cropping
        ↓
Image Preprocessing
        ↓
EasyOCR
        ↓
Text Cleaning
        ↓
License Plate Number
