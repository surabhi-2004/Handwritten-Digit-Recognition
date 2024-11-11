
# Digit Recognition with CNN and Pygame

This project is designed for digit recognition using a Convolutional Neural Network (CNN) model trained on 60,000 images and tested on 10,000 images and achieved an accuracy of 98% on the test set. It includes a Pygame-based application (app.py) to draw and predict handwritten digits in real-time. The CNN model is created and trained in hdr.ipynb.

# Project Overview

This project contains two main components:

1 --> hdr.ipynb: A Jupyter Notebook for creating and training a CNN model to recognize handwritten digits using the MNIST dataset.

2--> app.py: A Pygame application to draw and predict handwritten digits in real-time, utilizing the trained CNN model for recognition.

# File Descriptions

1 --> hdr.ipynb: This file includes the following steps:

Data preprocessing for the MNIST dataset.
Building and training a CNN model with Keras, including Dropout layers to prevent overfitting.
Saving the trained model in model/model.h5.

2 --> app.py: This Python file includes:

A Pygame application where users can draw digits.
Integration with the saved CNN model for real-time digit prediction.
Display of predicted digit on the screen.

# Setup and Installation
Prerequisites
Python 3.6 or later
numpy, matplotlib, keras, pygame, and opencv-python for image handling and drawing.
Install dependencies using:

~~~bash
pip install numpy matplotlib keras pygame opencv-python
~~~

Getting Started

1 --> Train the Model: Run hdr.ipynb to train the CNN model and save it to model/model.h5.

2 --> Run the Application: Execute app.py to open the Pygame digit board.

# Usage
--> Drawing Digits: Use your mouse to draw digits in the Pygame window.

-->Predicting Digits: The application will predict the drawn digit in real-time and display it on the screen.

# Screenshot Of Output Window
![Screenshot 2024-11-12 005712](https://github.com/user-attachments/assets/385010fa-67bb-4f76-b4a2-1011f1bf70cc)

