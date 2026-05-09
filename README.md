# A Deep Learning-Based Framework for Autonomous Driving Software in Electric Vehicles

**Roll No:** 2210991854  
**Name:** Llywellyn Sana Thaoroijam  
**University:** Chitkara University, Punjab  
**Mentor:** Dr. Simarjit Kaur, Associate Professor  
**Course:** CO-OP Project at Industry (Module-2)

---

## Repository Structure

```bash
ai-drive-2210991854/
│
├── CODE/
│   ├── AI_DRIVE_FINAL.ipynb
│   ├── PRERUN.ipynb
│   ├── yolo26n.pt
│   ├── yolov8n.pt
│   ├── yolov8n_trained.pt
│   ├── data/
│   └── runs/
│
├── PPT and REPORT/
│   ├── 2210991854_PPT.pptx
│   └── 2210991854_REPORT.docx
│
├── IPR Submission Proof/
│   └── Research Paper Submission.png
│
└── README.md
```

---

## Project Overview

This project presents a deep learning-based autonomous driving framework designed specifically for electric vehicles operating in complex and unstructured environments.

The framework combines:

- YOLOv8-based real-time object detection
- Lane detection and road analysis
- Dynamic object tracking
- Deep learning-based traffic environment understanding
- Real-time deployment workflow using Jupyter Notebook environment

---

## Key Features

- Real-Time Object Detection
- YOLOv8 Deep Learning Integration
- Traffic and Lane Analysis
- Autonomous Driving Simulation Workflow
- GPU Optimized Processing
- Dataset Preprocessing Pipeline

---

## Technologies Used

- Python 3.x
- YOLOv8 (Ultralytics)
- PyTorch
- OpenCV
- NumPy
- Jupyter Notebook
- CUDA / NVIDIA GPU Acceleration

---

## Virtual Environment Setup

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### macOS/Linux

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install ultralytics torch torchvision opencv-python numpy notebook matplotlib pandas
```

---

## Dataset Setup

This project uses the BDD100K dataset.

### Download Dataset

Download the dataset from:

http://bdd-data.berkeley.edu/

---

### Extract Dataset

After downloading, extract the dataset files inside the `100k` folder.

Example:

```bash
100k/
├── train/
├── val/
└── test/
```

---

### Add Images

Place all dataset images inside the corresponding `images` subfolders.

Examples:

```bash
train/images
val/images
test/images
```

---

### Add Labels

Download and place the label files inside the root dataset directories.

Examples:

```bash
train/
val/
test/
```

---

## PRERUN Command

Before training the model, run the PRERUN notebook to convert the labels into YOLO format.

```bash
PRERUN.ipynb
```

Run all cells in the notebook before starting training.

---

## Software Requirements

- Python 3.8 or higher
- PyTorch 2.0+
- CUDA 11.8+ (for GPU acceleration)
- OpenCV 4.8+
- NumPy 1.24+
- Jupyter Notebook

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

## How to Run

### Open Project Folder

```bash
cd CODE
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run Dataset Conversion

Open and run:

```bash
PRERUN.ipynb
```

### Run Main Project

Open and run:

```bash
AI_DRIVE_FINAL.ipynb
```

---

## Model Files

The repository includes pretrained and trained YOLO model weights:

- `yolo26n.pt`
- `yolov8n.pt`
- `yolov8n_trained.pt`

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

---

## Collaborator Access

This repository has been shared with: **cse.ph4e@chitkara.edu.in**

