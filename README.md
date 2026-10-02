# Handwritten Digit Recognition using CNN

## 📌 Project Overview

This project implements a handwritten digit recognition system using
Convolutional Neural Networks (CNN) with TensorFlow and Keras.

The model is trained using the MNIST dataset to recognize handwritten
digits from 0 to 9.

## 🎯 Objectives

- Recognize handwritten digits using Deep Learning.
- Train a CNN model using the MNIST dataset.
- Improve image recognition using convolutional layers.
- Evaluate the trained model using test accuracy.
- Visualize training and validation performance.
- Display predicted digit results.

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- MNIST Dataset

## 🧠 CNN Model Architecture

The model contains:

- Convolutional Layers
- Batch Normalization
- Max Pooling
- Dropout
- Flatten Layer
- Fully Connected Dense Layer
- Softmax Output Layer

The output layer contains 10 neurons representing digits 0 to 9.

## 📊 Dataset

The project uses the MNIST handwritten digit dataset.

- Training samples: 60,000
- Testing samples: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10
- Classes: 0–9

## ⚙️ Project Workflow

1. Load the MNIST dataset.
2. Normalize image pixel values.
3. Reshape images for CNN processing.
4. Apply data augmentation.
5. Build the CNN model.
6. Compile the model using Adam optimizer.
7. Train the model.
8. Save the best model.
9. Evaluate the model.
10. Generate predictions.
11. Visualize accuracy and loss.

## 📁 Project Structure

```text
AMMUDHA/
│
├── README.md
├── requirements.txt
│
├── source code/
│   └── MNIST CNN source code
│
├── dataset/
│
└── output/
    └── Training and prediction results
