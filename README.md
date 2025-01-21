# **Object Detection Using CNN**

A deep learning project to classify images using the CIFAR-10 dataset with a Convolutional Neural Network (CNN). This project implements a custom CNN architecture for object detection and integrates Gradio for a simple user interface to test image classification.

---

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Results](#results)
5. [Technologies Used](#technologies-used)
6. [Contributing](#contributing)

---

## **Overview**
This project builds a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset, a collection of 60,000 32x32 color images across 10 categories. It employs data augmentation, dropout regularization, and batch normalization to enhance the model's accuracy and prevent overfitting. Gradio is used to provide an interactive interface for testing image classification.

---

## **Features**
- CNN architecture with advanced techniques:
  - Data augmentation using `ImageDataGenerator`.
  - Dropout for regularization.
  - Batch normalization for stable training.
  - Learning rate scheduling and early stopping.
- Gradio-based interface for testing images in real-time.
- Model trained on CIFAR-10 dataset with 10 categories.

---

## **Dataset**
The project uses the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html), which contains 10 classes:
1. Airplane  
2. Automobile  
3. Bird  
4. Cat  
5. Deer  
6. Dog  
7. Frog  
8. Horse  
9. Ship  
10. Truck

---

## **Results**

### **Training Summary**

- **Model Architecture:** Sequential CNN with 4 convolutional blocks.  
- **Training Accuracy:** Approximately 88% (achieved during training).  
- **Validation Accuracy:** Approximately 85% (on validation data).  
- **Test Accuracy:** 83% (on CIFAR-10 test data).

### **Example Predictions**

| **Input**                  | **Prediction** | **Confidence** |
|----------------------------|----------------|----------------|
| Image of a dog             | Dog            | 95%            |
| Image of an airplane       | Airplane       | 92%            |

---

## **Technologies Used**

- **Frameworks/Libraries:** TensorFlow, Keras, Gradio  
- **Programming Language:** Python  
- **Dataset:** CIFAR-10  

---

## **Contributing**

Contributions are welcome! If you want to improve this project or fix issues, please:

1. Fork the repository.  
2. Make your changes.  
3. Submit a pull request.

---
