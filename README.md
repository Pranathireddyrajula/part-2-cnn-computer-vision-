# Computer Vision Problem Formulation and CNN Prototype

## Project Overview
This project focuses on building a Convolutional Neural Network (CNN) model for manufacturing defect image classification.

The goal is to classify product surface images into different categories such as:
- normal
- scratch
- dent
- stain

The project demonstrates how CNNs learn visual patterns using:
- Convolution
- Pooling
- Activation functions
- Dense layers

## Dataset Information
Dataset: Synthetic Manufacturing Defect Image Dataset
Classes:
- normal
- scratch
- dent
- stain
## Dataset Source

Dataset provided in the assignment shared Google Drive folder:
https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing

## Problem Type

This project represents an **Image Classification** problem because each image belongs to one specific class.

The CNN model predicts the category of a product image based on visual features.

## Steps Performed

### 1. Dataset Exploration
- Analyzed classes
- Counted images per class
- Visualized sample images
- Checked image dimensions

### 2. Image Preprocessing
- Resized images to fixed dimensions
- Normalized pixel values
- Split dataset into training and testing sets

### 3. CNN Model Creation
The CNN model includes:
- Convolution layers
- ReLU activation
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

### 4. Model Training and Evaluation
- Trained CNN model
- Evaluated testing accuracy
- Generated confusion matrix
- Visualized accuracy and loss curves
- Generated sample predictions

# TASK6: CNN Concept Explanation

## What is Convolution?

Convolution is a process used to extract important visual features such as edges, textures, and patterns from images.

## Why is Pooling Used?

Pooling reduces the size of feature maps while preserving important information. This helps reduce computation and overfitting.

## Why is ReLU Commonly Used in CNNs?

ReLU introduces non-linearity and helps CNN models learn complex visual patterns efficiently.

## Why are CNNs Better Than Regular Feed-Forward Networks for Images?

CNNs are designed specifically for image data. They automatically detect spatial patterns and require fewer parameters than traditional fully connected neural networks.

## Results

The CNN model successfully classified manufacturing defect images into different categories.

The model learned visual patterns effectively and achieved good classification performance on testing data.
## Conclusion

This project helped in understanding:
- CNN architecture
- Image preprocessing
- Convolution and pooling operations
- Deep learning for computer vision
- Image classification workflows

The project demonstrates how CNNs can be applied to real-world industrial inspection problems.