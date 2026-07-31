# 🔥 Smoke and Fire Detection using Detectron2

<div align="center">

# Smoke and Fire Detection using Detectron2

Object Detection model for detecting **Smoke** and **Fire** using the **Roboflow dataset** and **Detectron2**. The project trains a deep learning model for real-time fire and smoke detection and can be used in surveillance, forest monitoring, industrial safety, and early fire warning systems.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Detectron2](https://img.shields.io/badge/Detectron2-Object%20Detection-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Roboflow](https://img.shields.io/badge/Roboflow-Dataset-purple)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

## 📌 Overview

This project uses **Detectron2**, Facebook AI Research's object detection framework, to detect **Smoke** and **Fire** in images. The dataset was collected and annotated using **Roboflow**, and the model was trained using transfer learning with a pre-trained Faster R-CNN architecture.

The trained model can identify:

* 🔥 Fire
* 💨 Smoke

---

## 🚀 Features

* Detect smoke and fire simultaneously.
* Transfer learning using Detectron2.
* Roboflow dataset integration.
* Training, evaluation, and inference pipeline.
* Bounding box visualization.
* Easy deployment for real-time monitoring systems.

---

## 🛠️ Tech Stack

* Python
* PyTorch
* Detectron2
* OpenCV
* Roboflow
* Google Colab / Jupyter Notebook
* Matplotlib
* NumPy

---

## 📂 Dataset

Dataset was obtained from **Roboflow Universe** and exported in **COCO format** for Detectron2 training.

Dataset Structure:

```text
dataset/
│
├── train/
├── valid/
├── test/
├── train/_annotations.coco.json
├── valid/_annotations.coco.json
└── test/_annotations.coco.json
```

Classes:

```text
0 → Fire
1 → Smoke
```

---

## 📁 Project Structure

```text
Smoke-Fire-Detectron2/
│
├── dataset/
├── outputs/
├── notebooks/
├── inference/
├── models/
├── images/
├── train.py
├── inference.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Smoke-Fire-Detectron2.git
cd Smoke-Fire-Detectron2
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📦 Install Detectron2

```bash
pip install torch torchvision torchaudio
pip install opencv-python matplotlib numpy
pip install detectron2
```

---

## 🏋️ Model Training

Run:

```bash
python train.py
```

The trained model weights will be saved in:

```text
outputs/model_final.pth
```

---

## 📊 Evaluation

Evaluate the trained model on the validation dataset:

```bash
python evaluate.py
```

Metrics:

* mAP
* Precision
* Recall
* IoU

---

## 🔍 Inference

Run prediction on an image:

```bash
python inference.py
```

Example output:

```text
Fire: 96%
Smoke: 92%
```

---

## 🖼️ Sample Prediction

```text
Input Image
↓
Detectron2 Model
↓
Bounding Boxes
↓
Fire / Smoke Prediction
```

---

## 📈 Applications

* Forest fire detection
* Industrial safety monitoring
* Smart city surveillance
* Warehouse monitoring
* Early warning systems
* CCTV fire detection
* Disaster management

---

## 🧠 Model Architecture

This project uses:

```text
Detectron2
   │
Faster R-CNN
   │
ResNet-50 Backbone
   │
Feature Pyramid Network (FPN)
   │
Bounding Box Prediction
```

---

## 📋 Requirements

```text
Python >= 3.10
PyTorch
Detectron2
OpenCV
NumPy
Matplotlib
Roboflow
```

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Ayush Gautam**

B.Tech Artificial Intelligence & Machine Learning Engineering

GitHub: [https://github.com/your-username](https://github.com/Ayushgautam75/Smoke-and-Fire-Detection-using-Detectron2/edit/main/README.md)

LinkedIn: https://linkedin.com/in/your-linkedin

---

### ⭐ If you found this project useful, give it a star on GitHub!
# Smoke-and-Fire-Detection-using-Detectron2
