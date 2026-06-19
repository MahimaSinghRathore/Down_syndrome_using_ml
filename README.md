# Down Syndrome Detection from Facial Images Using Deep Learning

## Overview

This project focuses on the automated detection of Down Syndrome from facial images using Deep Learning techniques. The objective is to assist healthcare professionals by providing an AI-based screening tool that can identify facial characteristics associated with Down Syndrome.

The project implements and compares three deep learning architectures:

- Custom Convolutional Neural Network (CNN)
- ResNet50 (Transfer Learning)
- VGG16 (Transfer Learning)

Among the evaluated models, VGG16 achieved the highest performance with an accuracy of 85.19%.

---

## Problem Statement

Down Syndrome (Trisomy 21) is a genetic condition caused by the presence of an extra chromosome 21. Early identification is important because timely intervention can significantly improve developmental outcomes.

Traditional diagnosis methods require genetic testing and specialist consultation, which may not always be available in resource-constrained areas. This project explores facial image analysis using Deep Learning as a supportive screening approach.

---

## Features

- Facial image classification
- Automated feature extraction
- Transfer Learning using pre-trained models
- Comparative performance analysis
- Confusion Matrix visualization
- Training and validation performance monitoring

---

## Technologies Used

### Programming Language
- Python

### Deep Learning Frameworks
- TensorFlow
- Keras

### Libraries
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Seaborn
- Scikit-learn

---

## Models Implemented

### 1. Custom CNN
A baseline Convolutional Neural Network built from scratch using:

- Conv2D Layers
- Batch Normalization
- Max Pooling
- Dense Layers
- Dropout

### 2. ResNet50

Transfer Learning model using:

- Pre-trained ImageNet weights
- Residual Learning Architecture
- Global Average Pooling
- Dense Classification Layers

### 3. VGG16

Transfer Learning model using:

- Pre-trained ImageNet weights
- 13 Convolution Layers
- Custom Dense Layers
- Dropout Regularization

---

## Dataset

The dataset consists of facial images belonging to:

- Individuals with Down Syndrome
- Individuals without Down Syndrome

The data was divided into:

- Training Set
- Validation Set
- Testing Set

Images were resized to:

224 × 224 pixels

---

## Data Preprocessing

The following preprocessing techniques were applied:

- Image Resizing
- Pixel Normalization
- Data Augmentation
- Horizontal Flipping
- Rotation
- Zooming
- Brightness Adjustment

---

## System Architecture

Input Image

↓

Image Preprocessing

↓

Feature Extraction

(CNN / ResNet50 / VGG16)

↓

Dense Layers

↓

Binary Classification

↓

Prediction Output

---

## Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|---------|---------|---------|---------|---------|
| CNN | 75.47% | 0.77 | 0.75 | 0.75 |
| ResNet50 | 77.05% | 0.78 | 0.77 | 0.77 |
| VGG16 | 85.19% | 0.86 | 0.85 | 0.85 |

VGG16 demonstrated the best overall performance among all evaluated models.

---

## Results

### CNN
- Accuracy: 75.47%
- True Positives: 576
- True Negatives: 759

### ResNet50
- Accuracy: 77.05%
- True Positives: 614
- True Negatives: 749

### VGG16
- Accuracy: 85.19%
- True Positives: 674
- True Negatives: 833

VGG16 achieved the highest accuracy and lowest false positive rate, making it the most effective model in this study.

---

## Applications

- Medical Screening Assistance
- Healthcare Decision Support Systems
- Genetic Disorder Detection
- AI-Assisted Diagnosis
- Medical Research

---

## Future Improvements

- Larger and more diverse datasets
- Multi-syndrome classification
- Vision Transformer (ViT) implementation
- Explainable AI using Grad-CAM
- Mobile application deployment
- Real-time prediction system

---

## Disclaimer

This system is intended as a supportive screening tool only and should not replace professional medical diagnosis, genetic testing, or clinical evaluation.

---

## Author

Mahima Singh

B.Tech Computer Science Engineering

Jaypee University of Information Technology

GitHub: https://github.com/MahimaSinghRathore
