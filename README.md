# Fruit Classification using Convolutional Neural Networks

## Overview

This project implements a Convolutional Neural Network (CNN) for multi-class fruit image classification using TensorFlow and Keras. The model was trained on a custom subset of the Fruits-360 dataset containing eight fruit categories.
The project demonstrates the complete deep learning workflow, including dataset preparation, preprocessing, data augmentation, model development, training, evaluation, and prediction.

## Dataset

**Source:** Fruits-360 Dataset

**Selected Classes**

- Apple Granny Smith
- Banana
- Kiwi
- Mango
- Orange
- Pineapple
- Strawberry
- Watermelon

**Image Size:** 100 × 100 pixels

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Model Architecture

The CNN architecture consists of:

- Rescaling Layer
- Conv2D (16 filters)
- MaxPooling2D
- Conv2D (32 filters)
- MaxPooling2D
- Conv2D (64 filters)
- MaxPooling2D
- Dropout
- Flatten
- Dense (128 neurons)
- Output Layer

## Project Workflow

```
Dataset
    ↓
Preprocessing
    ↓
Data Augmentation
    ↓
CNN Model
    ↓
Training
    ↓
Validation
    ↓
Prediction

## Hyperparameters

| Parameter | Value |
|-----------|-------|
| Image Size | 100 × 100 |
| Batch Size | 32 |
| Optimizer | Adam |
| Loss Function | Sparse Categorical Crossentropy |
| Activation Function | ReLU |

## Results

The model successfully learned visual features from the selected fruit classes and achieved good classification performance on the validation dataset.

**Performance Evaluation**

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

## Repository Structure

Fruit-Classification-CNN
│
├── CNN_pro.ipynb
├── README.md
├── requirements.txt
└── images

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Fruit-Classification-CNN.git
```
Install dependencies:

```bash
pip install -r requirements.txt

Run the notebook:

```bash
jupyter notebook CNN_pro.ipynb

## Future Work

- Train on additional fruit classes.
- Apply transfer learning using MobileNetV2 or EfficientNet.
- Optimize hyperparameters.
- Deploy the model using Streamlit.

## Author

Shiva D.
B.Tech – Artificial Intelligence and Machine Learning
