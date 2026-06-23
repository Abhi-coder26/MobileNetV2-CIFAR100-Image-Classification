# MobileNetV2-CIFAR100-Image-Classification

## Overview

This project implements MobileNetV2 with Transfer Learning for image classification on the CIFAR-100 dataset. The model was trained, fine-tuned, and evaluated using TensorFlow and Keras in Google Colab. Performance analysis was conducted using multiple evaluation metrics, confusion matrix visualization, and external image testing.

## Dataset Information

Dataset: CIFAR-100

* Number of Classes: 100
* Total Images: 60,000
* Training Samples: 45,000
* Validation Samples: 5,000
* Test Samples: 10,000
* Image Resolution: 32 × 32 × 3

## Model Architecture

* MobileNetV2
* Transfer Learning
* Fine-Tuning
* TensorFlow / Keras Framework

## Performance Results

| Metric              | Value  |
| ------------------- | ------ |
| Training Accuracy   | 50.83% |
| Validation Accuracy | 56.34% |
| Test Accuracy       | 56.48% |
| Test Loss           | 1.7365 |
| Precision           | 56.50% |
| Recall              | 56.48% |
| F1 Score            | 55.85% |

## External Image Testing

* Images Tested: 11
* Correct Predictions: 9
* Incorrect Predictions: 2
* External Testing Accuracy: 81.82%

## Model Information

| Parameter                | Value       |
| ------------------------ | ----------- |
| Model Name               | MobileNetV2 |
| Total Parameters         | 3,070,884   |
| Trainable Parameters     | 812,900     |
| Non-Trainable Parameters | 2,257,984   |

## Training Configuration

* Optimizer: Adam
* Fine-Tuning Optimizer: SGD with Momentum
* Batch Size: 64
* Early Stopping
* ReduceLROnPlateau
* Model Checkpoint

## Project Components

* Data Preprocessing
* Transfer Learning using MobileNetV2
* Fine-Tuning
* Model Evaluation
* Performance Metrics Analysis
* Confusion Matrix Visualization
* Accuracy and Loss Curve Analysis
* External Image Testing

## Repository Structure

```text
README.md
MobileNetV2_CIFAR100_Dataset.ipynb
MobileNetV2_CIFAR100_Project_Report.pdf
mobilenetv2_cifar100_dataset.py
```

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Author

Abhishek Chaurasiya

B.Tech Information Technology

Research Internship Project

Indian Institute of Engineering Science and Technology (IIEST), Shibpur
