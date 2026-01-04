# Simple Image Classification (Cat vs Dog)

## Overview
This project classifies images of cats and dogs using a Convolutional Neural Network (CNN) in TensorFlow/Keras. The model is trained on 100x100 RGB images and predicts whether an image is a cat or a dog.

## Dataset
- `input.csv` – Training images  
- `labels.csv` – Training labels (0 for dog, 1 for cat)  
- `input_test.csv` – Test images  
- `labels_test.csv` – Test labels  

Images are reshaped to `(100, 100, 3)` and normalized before training.

## Requirements
- Python 3.8+  
- Libraries: `numpy`, `matplotlib`, `tensorflow`  

Install dependencies with:
```bash
pip install numpy matplotlib tensorflow
