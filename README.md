This repository contains code for a Convolutional Neural Network (CNN) model designed to distinguish between legitimate and unrelated social security images. The goal of this study is to create an automated approach for identifying false social security images to prevent fraud and identity theft.

Key Features:
CNN Architecture: We implemented a CNN architecture tailored for social security image classification.
Data Preprocessing: The repository includes scripts for data preprocessing, including image resizing, normalization, and augmentation.
Model Training: Scripts for model training using TensorFlow/Keras are provided, along with options for hyperparameter tuning.
Evaluation: Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.
Deployment: Guidelines for deploying the trained model in production environments are included, ensuring seamless integration into fraud prevention systems.
Dataset:
The dataset used for training and evaluation is not included in this repository due to privacy concerns. However, guidelines for obtaining similar datasets are provided.

Requirements:
Python 3.x
TensorFlow
Keras
NumPy
Matplotlib
numpy==1.21.5
opencv_python_headless==4.4.0.46
torch==1.10.2
