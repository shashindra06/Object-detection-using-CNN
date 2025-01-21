# Object-detection-using-CNN

A deep learning project to classify images using the CIFAR-10 dataset with a Convolutional Neural Network (CNN). This project implements a custom CNN architecture for object detection and integrates Gradio for a simple user interface to test image classification.


**Table of Contents**
Overview
Features
Dataset
Installation
Usage
Results
Technologies Used
Contributing


**Overview**
This project builds a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset, a collection of 60,000 32x32 color images across 10 categories. It employs data augmentation, dropout regularization, and batch normalization to enhance the model's accuracy and prevent overfitting. Gradio is used to provide an interactive interface for testing image classification.


**Features**
CNN architecture with advanced techniques:
Data augmentation using ImageDataGenerator.
Dropout for regularization.
Batch normalization for stable training.
Learning rate scheduling and early stopping.
Gradio-based interface for testing images in real-time.
Model trained on CIFAR-10 dataset with 10 categories.

**Dataset**
The project uses the CIFAR-10 dataset, which contains 10 classes:

Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck

**Installation**
To run the project locally, 
Clone this repository
Ensure you have the necessary libraries:

TensorFlow
Keras
Gradio
NumPy
OpenCV
Matplotlib

**Usage**
Run the training script to train the model:

Launch the Gradio interface for testing

Upload an image in the Gradio interface to see the predicted class.

**Results**
Training Summary
Model Architecture: Sequential CNN with 4 convolutional blocks.
Training Accuracy: Approximately 88% (achieved during training).
Validation Accuracy: Approximately 85% (on validation data).
Test Accuracy: 83% (on CIFAR-10 test data).
Example Predictions
Input: Image of a dog.
Prediction: Dog.
Confidence: 95%.
Input: Image of an airplane.
Prediction: Airplane.
Confidence: 92%.


**Technologies Used**
Frameworks/Libraries: TensorFlow, Keras, Gradio.
Programming Language: Python.
Dataset: CIFAR-10

.
**Contributing**
Contributions are welcome! If you want to improve this project or fix issues, please:

Fork the repository.
Make your changes.
Submit a pull request.
