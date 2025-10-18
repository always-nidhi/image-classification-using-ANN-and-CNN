# Image Classification using ANN and CNN

This project implements image classification on the CIFAR-10 dataset using two deep learning models:  

1. Artificial Neural Network (ANN)  
2. Convolutional Neural Network (CNN)  

It compares the performance of both models and demonstrates the effectiveness of CNN for image-based tasks.

---

## Features
- Image preprocessing and normalization  
- ANN and CNN architectures implemented using TensorFlow/Keras  
- Model training, evaluation, and comparison  
- Classification report for performance analysis  

---

## Tech Stack
- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Dataset
CIFAR-10: 60,000 32×32 color images, divided into 10 classes:  
`airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck`  

- Training images: 50,000  
- Testing images: 10,000  

---

## How to Run
```bash
git clone https://github.com/yourusername/image-classification-using-ANN-and-CNN.git
cd image-classification-using-ANN-and-CNN
pip install -r requirements.txt
python train.py
