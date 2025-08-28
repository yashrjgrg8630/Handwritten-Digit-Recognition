# Handwritten-Digit-Recognition-MNIST

**Short Description:**  
Convolutional Neural Network (CNN) model for handwritten digit recognition using the MNIST dataset. Achieved **98% accuracy** on Kaggle Digit Recognizer competition.

---

## Table of Contents
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Model Architecture](#model-architecture)  
4. [Results](#results)  
5. [How to Run](#how-to-run)  
6. [Files](#files)  
7. [References](#references)  

---

## Overview
This project implements a **Convolutional Neural Network (CNN)** for recognizing handwritten digits from the **MNIST dataset**. The model has been trained and tested to achieve high accuracy and is suitable for digit recognition tasks.

**Key Features:**  
- Uses CNN for feature extraction and classification  
- Trains on the MNIST dataset (28x28 grayscale images)  
- Achieves **98% accuracy** on Kaggle Digit Recognizer

---

## Dataset
The MNIST dataset contains **70,000 images** of handwritten digits (0–9). It is divided into:  
- **Training set:** 60,000 images  
- **Test set:** 10,000 images  

**Image characteristics:**  
- Grayscale (1 channel)  
- 28x28 pixels  

**Source:** [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

---

## Model Architecture
The model uses a **CNN** with the following layers:  
1. **Convolutional Layer 1:** 32 filters, 3x3 kernel, ReLU activation  
2. **MaxPooling Layer 1:** 2x2 pool size  
3. **Convolutional Layer 2:** 64 filters, 3x3 kernel, ReLU activation  
4. **MaxPooling Layer 2:** 2x2 pool size  
5. **Flatten Layer**  
6. **Dense Layer:** 128 neurons, ReLU activation  
7. **Output Layer:** 10 neurons (softmax activation)  

**Optimizer:** Adam  
**Loss Function:** Categorical Crossentropy  

---

## Results
- **Training Accuracy:** ~99%  
- **Validation Accuracy:** ~98%  
- Achieved top performance in the **Kaggle Digit Recognizer competition**

---
```bash
git clone https://github.com/your-username/Handwritten-Digit-Recognition-MNIST.git
