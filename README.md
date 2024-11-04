# Tumor Detection Using Machine Learning

## Overview

This project aims to develop a machine learning-based system for detecting brain tumors from MRI images. The system utilizes Histogram of Oriented Gradients (HOG) for feature extraction and various classification algorithms, including K-Nearest Neighbors (KNN), Support Vector Classifier (SVC), Decision Tree, Random Forest, AdaBoost, Gradient Boosting, and XGBoost, to classify the images.

## Features

- **Image Processing**: The project processes MRI images to extract meaningful features for tumor classification.
- **Model Training**: Multiple machine learning models are trained and evaluated for their performance in tumor detection.
- **Prediction**: Users can upload MRI images, and the system will predict whether the image indicates a brain tumor and its type.
- **PDF Report Generation**: The system generates a PDF report containing the prediction results and medical advice based on the findings.

## Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost
- Tkinter (for GUI)
- FPDF (for PDF report generation)

## Dataset

The model is trained on a dataset containing MRI images of brain tumors, classified into the following categories:
- Glioma
- Meningioma
- Pituitary
- No tumor

## Getting Started

### Prerequisites

Make sure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).




