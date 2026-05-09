# A Deep Learning-Based Framework for Autonomous Driving Software in Electric Vehicles

**Roll No:** 2210991854  
**Name:** Llywellyn Sana Thaoroijam  
**University:** Chitkara University, Punjab  
**Mentor:** Dr. Simarjit Kaur, Associate Professor  
**Course:** CO-OP Project at Industry (Module-2)

---

## Repository Structure

```bash
Autonomous-Driving-EV-Framework/
│
├── dataset/
│   └── BDD100K/
│
├── models/
│   └── yolov8_model.pt
│
├── app/
│   ├── app.py
│   ├── templates/
│   └── static/
│
├── detection/
│   ├── object_detection.py
│   ├── lane_detection.py
│   └── path_planning.py
│
├── training/
│   ├── train.py
│   └── preprocessing.py
│
├── results/
│   ├── confusion_matrix.png
│   ├── loss_curves.png
│   └── validation_predictions.png
│
├── report/
│   └── COOP2_Project_Report_Llywellyn.docx
│
└── README.md
```

---

## Project Overview

This project presents a deep learning-based autonomous driving framework designed specifically for electric vehicles operating in complex and unstructured environments.

The framework combines:

- YOLOv8-based real-time object detection
- Lane detection using Canny edge detection
- Polynomial curve fitting for road tracking
- Dynamic path planning
- Flask-based real-time deployment interface

---

## Key Features

- Real-Time Object Detection
- Lane Detection Pipeline
- Dynamic Path Planning
- Explainable AI Integration
- Web-Based Deployment
- GPU Optimized (35–55 FPS)

---

## Technologies Used

- Python 3.x
- YOLOv8 (Ultralytics)
- PyTorch
- TensorFlow
- OpenCV
- Flask
- NumPy
- CUDA / NVIDIA GPU Acceleration

---

## Virtual Environment Setup

### Create and Activate Virtual Environment

```bash
# Create virtual environment
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on macOS/Linux
source venv/bin/activate
```

### Install Dependencies

```bash
pip install ultralytics opencv-python flask torch torchvision numpy
```

---

## Software Requirements

- Python 3.8 or higher
- PyTorch 2.0+
- CUDA 11.8+ (for GPU acceleration)
- OpenCV 4.8+
- Flask 2.3+
- NumPy 1.24+

---

## Minimum Hardware Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| CPU | Intel i5 / AMD Ryzen 5 | Intel i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| GPU | NVIDIA GTX 1060 (6GB VRAM) | NVIDIA RTX 3060+ (8GB+ VRAM) |
| Storage | 50 GB free space | 100 GB SSD |
| OS | Windows 10/11, Linux, macOS | Windows 11, Ubuntu 22.04+ |

---

## Dataset

The project uses a curated subset of the BDD100K dataset for training and validation under diverse driving conditions.

---

## How to Run

### Install Dependencies

```bash
pip install ultralytics opencv-python flask torch torchvision numpy
```

### Run the Flask Application

```bash
python app/app.py
```

### Train the Model

```bash
python training/train.py
```

---

## Performance Summary

| Metric | Result |
|---|---|
| Real-Time FPS | 35–55 FPS |
| Detection Framework | YOLOv8 |
| Lane Detection | Canny + Polynomial Fitting |
| Deployment | Flask Web Application |
| Hardware | NVIDIA GPU |

---

## Future Improvements

- LiDAR and Radar sensor fusion
- Semantic segmentation integration
- Reinforcement learning
- Embedded edge-device optimization
- Improved low-light performance

---

## Acknowledgement

Special thanks to **Dr. Simarjit Kaur** for her guidance and support throughout the project development process.

---

## Author

**Llywellyn Sana Thaoroijam**  
Bachelor of Engineering — Computer Science and Engineering  
Chitkara University, Punjab
