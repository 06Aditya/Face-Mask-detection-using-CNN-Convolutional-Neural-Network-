# Face Mask Detection using CNN

A computer vision project that detects whether a person is wearing a face mask in real-time using Convolutional Neural Networks (CNN) and OpenCV.

---

## Overview

This project builds a real-time face mask detection system using deep learning. It classifies faces from webcam input as **with mask** or **without mask**.

The model is trained on an image dataset and deployed using OpenCV for live detection.

---

## Dataset

* Total images: 1376
* With mask: 690
* Without mask: 686

The dataset consists of labeled face images used to train the classification model.

---

## Approach

### Model Training

* Built a CNN model using Keras
* Trained on labeled face mask dataset
* Learned features to distinguish masked vs unmasked faces

---

### Real-Time Detection

* Used OpenCV for webcam input
* Detected faces in real-time
* Applied trained model to classify each face

---

## Workflow

1. Load and preprocess dataset
2. Train CNN model
3. Save trained model
4. Capture webcam input using OpenCV
5. Detect faces and classify mask usage

---

## Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy

---

## Project Structure

```id="1y8k2q"
Face-Mask-Detection/
│── train.py
│── detect.py
│── dataset/
│── model/
│── README.md
```

---

## Installation

```bash id="0z7m4x"
pip install tensorflow opencv-python numpy
```

---

## How to Run

### Train the Model

```bash id="5n2r8c"
python train.py
```

---

### Run Real-Time Detection

```bash id="9k3v1t"
python detect.py
```

---

## Features

* Real-time face mask detection
* Webcam-based input
* Lightweight and easy to use

---

## Future Improvements

* Improve model accuracy with larger dataset
* Use advanced architectures (MobileNet, EfficientNet)
* Deploy as a web or mobile application
* Add face tracking for better performance

---

## Contact

* LinkedIn: https://www.linkedin.com/in/aditxya/

---

If you found this project useful, consider giving it a ⭐
