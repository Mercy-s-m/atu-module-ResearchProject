# Facial Recognition in Non-Ideal Conditions Using Deep Learning

This repository contains the code, experiments, and models developed for optimizing deep learning algorithms to improve facial recognition performance in non-ideal conditions, such as low light, occlusions, and extreme angles. The project utilizes multiple deep learning techniques, including Convolutional Neural Networks (CNNs), Multi-task Cascaded Convolutional Networks (MTCNN), and data augmentation to enhance model robustness and accuracy.

## Project Overview

The goal of this project is to optimize facial recognition models to improve their performance under challenging real-world conditions, including:

Low lighting environments
Partial occlusions (e.g., glasses, masks)
Extreme facial angles
We employ deep learning models like CNNs with ResNet-Inception, MTCNN for detection, and advanced data augmentation techniques to ensure the models are robust in these scenarios.

## Dataset

We used the Labeled Faces in the Wild (LFW) dataset for training and evaluation. This dataset contains over 13,000 labeled facial images captured in uncontrolled, real-world environments.

## Methods

Data Augmentation: Techniques such as random cropping, rotation, noise addition, and color jittering were applied to improve model generalization in non-ideal conditions.

**Facial Detection:**
Haar Cascade Classifier: Used for initial facial detection in the dataset.

**Facial Recognition:**
CNN Model: Implemented with ResNet-Inception for feature extraction and classification.
Multi-task Cascaded Convolutional Networks (MTCNN): Used for precise detection and alignment of facial landmarks.

## Results

**The optimized models achieved:**

Improved accuracy (up to 85%) on challenging test cases with low light and occlusions.
Better handling of difficult conditions such as extreme angles with the use of data augmentation.

