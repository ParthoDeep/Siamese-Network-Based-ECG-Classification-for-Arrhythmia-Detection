# Siamese Convolutional Neural Network-Based ECG Classification for Arrhythmia Detection

## Overview
Accurately classifying ECG signals is challenging due to **imbalanced datasets** and **patient-specific variations**. To address this, the proposed **Few-Shot Learning-based SCNN** captures subtle differences between ECG patterns, enabling **better generalization** even with limited training data.
This project implements **ECG signal classification** using a **Siamese Convolutional Neural Network (SCNN)** trained with **contrastive loss**. 

Instead of directly predicting classes, the model learns **feature embeddings**, where **similar ECG signals are mapped close together** and **dissimilar signals are mapped farther apart**.  

The model demonstrates potential for **real-time ECG monitoring**, **arrhythmia detection**, and improved **clinical decision support**.
---

## Features
- Siamese CNN architecture for ECG spectrograms  
- Multi-class classification support (e.g., 3-class ECG dataset)  
- Contrastive loss for similarity learning   
- Confusion matrix, accuracy, precision, recall, F1-score  
- ROC and Precision-Recall curves
## Requirements
numpy==1.24.0
opencv-python==4.8.0
scikit-learn==1.3.0
matplotlib==3.8.0
seaborn==0.12.3
