# CIFAR-10 Image Classification (CNN)

This project implements a convolutional neural network (CNN) for classifying images from the CIFAR-10 dataset.  
The model uses TensorFlow, data augmentation, and a clean `tf.data` pipeline for efficient training.

## Features
- Modern CNN architecture with BatchNorm + ReLU  
- Data augmentation  
- tf.data pipeline  
- Training curves and evaluation  
- Achieves ~60–70% accuracy depending on run  

## How to Run
1. Clone the repo  
2. Install dependencies  
3. Open the notebook  
4. Run all cells (dataset auto-downloads)

## Requirements
```bash
pip install tensorflow numpy matplotlib
