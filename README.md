# ParkinsonsDiseaseDetection-via-Handwritten-Drawings
This project works in prediction of parkinson's disease using handwritten drawings of several spirals and waves images data of both healthy and people with parkinsonism.

This project focuses on early detection of Parkinson’s Disease (PD) using computer vision techniques, particularly deep learning models applied to images of hand-drawn spirals and waves. By leveraging Convolutional Neural Networks (CNNs) and transfer learning, this system distinguishes between healthy individuals and those affected by PD.

# Project Motivation
Parkinson’s is a progressive neurological disorder that significantly impairs motor function. Traditional diagnostic methods often rely on clinical observations, which can be subjective and lead to delayed diagnosis. This project provides a non-invasive, cost-effective, and real-time solution for early detection using handwriting analysis.


* Utilizes CNN-based transfer learning using InceptionV3 and ResNet50
* Input images include spiral and wave patterns drawn by individuals
* Real-time prediction using webcam integration
* High classification performance with evaluation metrics including accuracy, confusion matrix, and classification report


## Methodology
1. Data Input
Images of spiral and wave drawings, which are affected by tremors in PD patients, are used as input.
2. Model Architecture
Transfer Learning with frozen lower layers and fine-tuned top layers.

### Models used:
* InceptionV3
* ResNet50

3. Training & Evaluation
* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Metrics: Accuracy, Confusion Matrix, Classification Report

4. Real-Time Prediction
A pipeline was developed using OpenCV to capture live drawings via webcam, classify them in real-time, and display the prediction result.

## Technologies Used
* Python
* TensorFlow / Keras
* OpenCV
* Scikit-learn
* Matplotlib 

## Key Features
* Early Detection: Allows for timely intervention
* High Accuracy: Pre-trained CNNs tuned to the task
* Transfer Learning: Speeds up training and improves performance on limited data
* Webcam Integration: Live demo functionality
