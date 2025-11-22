**Customized CNN Architecture for ECG Image-Based Classification of Cardiovascular Diseases**

**Published in IEEE – SSITCON 2024**

**Paper Link** : https://ieeexplore.ieee.org/document/10796798/

This repository contains the implementation, documentation, and IEEE publication for a deep-learning approach to classify cardiovascular diseases using ECG images. The project introduces a customized Xception-based Convolutional Neural Network (CNN) to enhance feature extraction from ECG images and significantly improve disease classification accuracy.

**1. Overview**

Cardiovascular diseases are among the leading causes of death worldwide. Traditional ECG signal-based analysis often loses structural and spatial information.
This research transforms ECG signals into images and applies a deep learning–based image classification model to detect heart conditions more accurately.

Our customized Xception model achieved an outstanding 98.43% accuracy, outperforming classical CNN models and machine learning approaches.

**2. Key Contributions**

✔ Designed a custom CNN architecture based on Xception with enhanced classification layers

✔ Developed a complete ECG image preprocessing pipeline including cropping, grayscale conversion, and augmentation

✔ Extracted deep features and trained multiple ML classifiers

✔ Achieved significantly higher performance compared to traditional models

✔ Demonstrated the effectiveness of using image-based ECG classification

**3. Dataset**

The dataset consists of ECG images covering four cardiovascular conditions:

Myocardial Infarction

Abnormal Heartbeat

History of MI

Normal Condition

**Images go through preprocessing steps such as:**

Cropping

Grayscale conversion

Normalization

Data augmentation


**4. Proposed Architecture**

The model is built on the Xception base architecture with additional custom layers:

Global Average Pooling

Dense (1024 units, ReLU)

Dropout (0.5)

Dense output layer (4-class Softmax)

This combination allows the model to learn deep spatial patterns present in ECG images.

**5. Experimental Results**

| Model                          | Accuracy   |
| ------------------------------ | ---------- |
| **Customized Xception (Ours)** | **98.43%** |
| GAN-LSTM                       | 97.8%      |
| XGBoost                        | 92.0%      |
| VGG-16                         | 88.16%     |


**6. Technologies Used**

Python

TensorFlow / Keras

Xception CNN

NumPy, Pandas

Matplotlib, Seaborn

Machine Learning Classifiers

Google Colab


