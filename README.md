# Industrial Defect Detection using CNN
Industrial surface defect classification using CNN and TensorFlow on the NEU-DET dataset.


## Overview

This project aims to classify industrial steel surface defects using Computer Vision and Deep Learning.

A Convolutional Neural Network (CNN) was trained on the NEU-DET dataset containing six categories of defects.

## Dataset

NEU-DET Dataset

* Total Images: 1800
* Training Images: 1440
* Validation Images: 360
* Classes:

  * Crazing
  * Inclusion
  * Patches
  * Pitted Surface
  * Rolled-in Scale
  * Scratches

## Technologies Used

* Python
* TensorFlow / Keras
* Google Colab
* NumPy
* Matplotlib
* Scikit-Learn

## Model Architecture

The model is based on a Convolutional Neural Network (CNN) composed of:

* Convolution Layers
* MaxPooling Layers
* Dense Layers
* Softmax Output Layer

## Results

* Training Accuracy: 95.8%
* Validation Accuracy: 90.8%

The model successfully classifies six different industrial defects.

## Example Prediction

Defect detected: scratches

Confidence: 99.6%

## Future Improvements

* Transfer Learning (ResNet50, MobileNetV2)
* Go / No-Go Inspection System
* Defect Localization using XML annotations
* Web Interface Deployment
