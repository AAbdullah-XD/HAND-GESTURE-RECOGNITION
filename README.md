# Hand Gesture Recognition using CNN

## Project Overview
This project implements a Hand Gesture Recognition system using a Convolutional Neural Network (CNN) trained on the LeapGestRecog dataset. The model classifies different hand gestures and lays the foundation for real-time gesture recognition using a laptop camera.

## Features
- Image Preprocessing: Converts images to grayscale, resizes them to 64x64, flattens, normalizes pixel values, and encodes gesture labels.
- Deep Learning Model: A CNN built with TensorFlow/Keras to classify hand gestures.
- Training & Evaluation: Uses an 80-20 train-test split, plots accuracy/loss graphs, and evaluates performance with a confusion matrix.
- Visualization: Displays sample images before training and provides model evaluation metrics.
- Future Scaling: Integrating real-time gesture detection using a laptop camera.

## Tech Stack
- Python
- TensorFlow/Keras
- OpenCV
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for evaluation metrics)

## Dataset
The dataset used is LeapGestRecog, a collection of hand gesture images categorized into different classes. The dataset is loaded and preprocessed before training the model.

## Future Work
- Implement real-time gesture recognition using OpenCV and TensorFlow.
- Improve model accuracy with data augmentation.
- Optimize CNN architecture for faster inference.

## Owner
- Abdullah Bilal
