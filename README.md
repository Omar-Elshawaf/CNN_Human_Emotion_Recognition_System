# CNN_Human_Emotion_Recognition_System

A deep learning–based human emotion recognition system that utilizes a Convolutional Neural Network (CNN) architecture to classify facial emotions from image frames. The system focuses on extracting discriminative spatial features from aligned facial regions to accurately recognize human emotional states, with a design suitable for real-time deployment.

---

## Project Overview

This project implements a complete facial emotion recognition pipeline using the FER-2013 dataset, combining robust face detection, facial alignment, and modern CNN architectures.  
The system is designed with both accuracy and real-time performance in mind and serves as the emotion recognition module within a larger human behavior analysis framework.

---

## Objectives

- Accurately classify human facial emotions from images
- Apply face detection and alignment to improve recognition robustness
- Compare multiple optimization algorithms and CNN architectures
- Build a model suitable for real-time emotion detection
- Follow a clean, modular, and reproducible deep learning workflow

---

## System Pipeline

Input Image / Video Frame
↓
Face Detection (MTCNN / Dlib)
↓
Facial Landmark Alignment (Dlib 68 landmarks)
↓
CNN Feature Extraction
↓
Emotion Classification

---

## Model Architecture

The system is built around CNN-based classifiers, with experiments including:

- Mini-Xception CNN
- EfficientNetB0 with 128×128 input resolution

These architectures were selected to balance feature extraction quality, computational efficiency, and suitability for real-time inference.

---

## Tools and Libraries

- Python
- TensorFlow and Keras
- OpenCV
- Dlib
- MTCNN
- NumPy
- Matplotlib
- Seaborn

---

## Dataset

### FER-2013

- Public facial emotion recognition dataset
- Seven emotion classes:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Sad
  - Surprise
  - Neutral

---

## Data Preprocessing

- Automatic dataset download and setup
- Face detection using MTCNN
- Facial alignment using Dlib 68 facial landmarks
- Image resizing and normalization
- Directory-based dataset organization
- Train and validation split

---

## Training Strategy

### Optimizers Compared

- Stochastic Gradient Descent (SGD) without momentum
- Adam optimizer
- Adagrad optimizer

### Training Features

- GPU detection and configuration
- Label smoothing to improve generalization
- Batch-based training
- Accuracy and loss monitoring across epochs

---

## Performance Evaluation

- Validation accuracy comparison across different optimizers
- Architecture-level performance analysis
- Stability and convergence behavior evaluation
- Practical accuracy suitable for real-time emotion recognition

---

## Project Strengths

- Integration of facial alignment using Dlib landmarks to improve robustness against pose and scale variations
- Use of modern and efficient CNN architectures such as Mini-Xception and EfficientNet
- Systematic comparison of multiple optimizers to analyze training dynamics
- Design suitable for real-time emotion recognition systems
- Clean and modular experimental workflow with reproducible results

<img width="793" height="624" alt="image" src="https://github.com/user-attachments/assets/6982ad8d-e863-4250-b4e9-f8ecfcd38e27" />
<img width="1001" height="470" alt="image" src="https://github.com/user-attachments/assets/8ac2e011-5caa-4423-bc54-213e99fac7e0" />
<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/b3f202a2-4e21-4671-86a5-aeaeb2e6fb61" />
<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/b637ef5c-46ce-4a86-ae4d-10d2a9911d45" />
<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/e63edc9d-2d36-436f-8954-182e99b62ee1" />
<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/dcd92910-3108-4b5b-9b6a-73f6019d333d" />

---

