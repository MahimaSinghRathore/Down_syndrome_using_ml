# Down Syndrome Detection from Facial Images Using Deep Learning

A research-oriented academic group project that explores the detection of Down Syndrome from facial images using Deep Learning techniques. The project compares CNN, ResNet50, and VGG16 models, with **VGG16 achieving the highest accuracy of 85.19%**. This repository contains Jupyter notebooks, experimental analysis, and an unpublished research manuscript documenting the project's methodology and findings.

---

## Overview

This project investigates the use of Deep Learning for the automated detection of Down Syndrome from facial images. The objective is to develop an AI-assisted screening system that can help identify facial characteristics associated with Down Syndrome and support healthcare professionals during the screening process.

Three deep learning architectures were implemented and evaluated:

- Custom Convolutional Neural Network (CNN)
- ResNet50 (Transfer Learning)
- VGG16 (Transfer Learning)

Among all evaluated models, **VGG16 achieved the best performance with an accuracy of 85.19%**.

> **Note:** This repository includes an **unpublished research manuscript** prepared as part of this academic project. It has **not** been submitted to or published in any journal or conference.

---

## Repository Contents

- Jupyter Notebooks (.ipynb)
- Data preprocessing pipeline
- Model training and evaluation
- Performance comparison of CNN, ResNet50, and VGG16
- Experimental results
- Unpublished research manuscript (PDF)

---

## Problem Statement

Down Syndrome (Trisomy 21) is a genetic condition caused by the presence of an extra chromosome 21. Early diagnosis is important because timely intervention can significantly improve developmental outcomes.

Traditional diagnosis relies on genetic testing and specialist consultation, which may not always be accessible in resource-limited settings. This project explores Deep Learning-based facial image analysis as a supportive screening approach.

---

## Features

- Facial image classification
- Automated feature extraction
- Transfer Learning using pre-trained models
- Comparative model evaluation
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

A baseline Convolutional Neural Network developed from scratch using:

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
- 13 Convolutional Layers
- Custom Dense Layers
- Dropout Regularization

---

## Dataset

The dataset consists of facial images from:

- Individuals with Down Syndrome
- Individuals without Down Syndrome

Dataset split:

- Training Set
- Validation Set
- Testing Set

Image Size:

**224 × 224 pixels**

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

```text
Input Image
      │
      ▼
Image Preprocessing
      │
      ▼
Feature Extraction
(CNN / ResNet50 / VGG16)
      │
      ▼
Dense Layers
      │
      ▼
Binary Classification
      │
      ▼
Prediction Output
```

---

## Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|--------:|---------:|
| CNN | 75.47% | 0.77 | 0.75 | 0.75 |
| ResNet50 | 77.05% | 0.78 | 0.77 | 0.77 |
| **VGG16** | **85.19%** | **0.86** | **0.85** | **0.85** |

VGG16 demonstrated the best overall performance among the evaluated models.

---

## Results

### CNN

- Accuracy: **75.47%**
- True Positives: **576**
- True Negatives: **759**

### ResNet50

- Accuracy: **77.05%**
- True Positives: **614**
- True Negatives: **749**

### VGG16

- Accuracy: **85.19%**
- True Positives: **674**
- True Negatives: **833**

VGG16 achieved the highest overall accuracy and demonstrated the best classification performance among the implemented models.

---

## Applications

- AI-assisted Medical Screening
- Healthcare Decision Support Systems
- Genetic Disorder Detection
- Medical Research
- Educational Research in Deep Learning

---

## Future Improvements

- Larger and more diverse datasets
- Multi-syndrome classification
- Vision Transformer (ViT)
- Explainable AI using Grad-CAM
- Mobile application deployment
- Real-time prediction system

---

## Research Manuscript

This repository contains an **unpublished research manuscript** prepared as part of this academic project. The manuscript documents the project methodology, data preprocessing, model implementation, experiments, and comparative analysis.

> **Note:** The manuscript is shared for educational and portfolio purposes only and has **not been published or peer-reviewed**.

---

## Repository Note

This repository is maintained as part of my personal GitHub portfolio and contains my copy of the group's implementation, documentation, and research manuscript.

---

## Project Team

- Yugam Jain
- Ekansh Gupta
- Mahima Singh
- Aryan Verma

**Project Supervisor:** Dr. Nishant Sharma

Department of Computer Science & Engineering

Jaypee University of Information Technology (JUIT)

---

## Disclaimer

This project is intended solely for educational and research purposes. It is designed as a supportive AI-based screening tool and should **not** be used as a substitute for professional medical diagnosis, genetic testing, or clinical evaluation.

---

## Author

**Mahima Singh**

B.Tech, Computer Science Engineering

Jaypee University of Information Technology (JUIT)

GitHub: https://github.com/MahimaSinghRathore
