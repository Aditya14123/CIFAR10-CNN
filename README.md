# CIFAR-10 Image Classification (CNN)

This project implements a convolutional neural network (CNN) for classifying images from the CIFAR-10 dataset.  
The final model was trained using `tf.data`, data augmentation, and a modern CNN architecture.

## Project Contents
- `CIFAR10_CNN.ipynb` — Full training notebook   
- `README.md` — Project documentation

## Dataset
CIFAR-10 is automatically downloaded by TensorFlow:
```python
from tensorflow.keras.datasets import cifar10
