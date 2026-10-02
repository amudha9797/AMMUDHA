# Handwritten Digit Recognition using Deep Learning

## 📌 Project Overview

This project implements a handwritten digit recognition system using
Deep Learning with TensorFlow and Keras.

The model is trained on the **MNIST handwritten digit dataset** to
recognize digits from **0 to 9**.

## 🎯 Objectives

- Recognize handwritten digits automatically.
- Train a neural network using the MNIST dataset.
- Evaluate the model using test accuracy.
- Visualize training accuracy and loss.
- Display predicted digit results.

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- MNIST Dataset

## 🧠 Model Architecture

The neural network consists of:

- Flatten Layer – converts 28×28 images into a single vector
- Dense Layer – 512 neurons with ReLU activation
- Dropout – 20%
- Dense Layer – 256 neurons with ReLU activation
- Dropout – 20%
- Output Layer – 10 neurons with Softmax activation

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

- Training samples: 60,000
- Test samples: 10,000
- Image size: 28 × 28 pixels
- Classes: 10 digits (0–9)

## ⚙️ Project Workflow

1. Load the MNIST dataset.
2. Normalize image pixel values.
3. Convert labels into categorical format.
4. Build the neural network.
5. Compile the model using Adam optimizer.
6. Train the model.
7. Evaluate test accuracy.
8. Generate accuracy and loss graphs.
9. Predict handwritten digits.

## 📁 Project Structure

```text
AMMUDHA/
│
├── README.md
├── source-code/
│   └── mnist_digit_recognition.py
│
├── dataset/
│   └── README.md
│
├── output/
│   ├── accuracy_loss_graph.png
│   └── predictions.png
│
└── requirements.txt
