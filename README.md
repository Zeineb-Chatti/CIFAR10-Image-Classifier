# CIFAR-10 Image Classifier

## Overview
This project classifies small 32x32 RGB images from the **CIFAR-10 dataset** into 10 categories using a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras.

---

## Dataset
The CIFAR-10 dataset contains **60,000 images** split into:

- 50,000 training images  
- 10,000 test images  

**10 Classes:**
- Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

---

## Model Architecture
- **Conv2D layers** with ReLU activation  
- **MaxPooling2D layers** for downsampling  
- **Flatten** to convert features to 1D  
- **Dense layers** for classification  
- **Dropout** to prevent overfitting  
- **Softmax output** for 10 classes  

---

## Training
- **Epochs:** 20  
- **Batch size:** 64  
- **Optimizer:** Adam  
- **Loss function:** Categorical Crossentropy  
- **Validation split:** 20%

---

## How to Use
1. Load the trained model.
2. Predict new images.

---

## Requirements
Python 3.x
TensorFlow / Keras
NumPy
Matplotlib
