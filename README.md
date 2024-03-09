# Semi-Supervised Learning with FixMatch for Brain Tumour Detection and Classification

## Overview

This project aims to leverage semi-supervised learning techniques, specifically FixMatch, and EfficientNet backbone, to detect and classify brain tumours from medical imaging data. FixMatch is a state-of-the-art semi-supervised learning algorithm that combines the benefits of labeled and unlabeled data to improve model performance.

## Motivation

Brain tumour detection and classification are crucial tasks in medical diagnostics. However, obtaining labeled medical imaging data is often expensive and time-consuming. By utilizing semi-supervised learning techniques, we aim to improve the efficiency and accuracy of brain tumour detection and classification while reducing the need for extensive labeled data.

## Methodology

The methodology involves the following steps:

1. **Data Collection**: Gather a dataset of brain MRI scans containing both labeled and unlabeled samples.
2. **Preprocessing**: Preprocess the MRI images to ensure uniformity and remove noise.
3. **Model Training**:
   - Train a deep neural network model using the FixMatch algorithm.
   - Use the labeled data for supervised learning and the unlabeled data for pseudo-label generation.
   - Employ data augmentation techniques to enhance model generalization.
4. **Model Evaluation**: Evaluate the trained model using various metrics such as accuracy, sensitivity, specificity, and F1 score.
5. **Inference**: Deploy the trained model for real-world brain tumour detection and classification tasks.

## Requirements

- Python
- NumPy
- PyTorch
- Torchvision
- Tensorboard
- efficientnet_pytorch

## Acknowledgements

This project utilizes the FixMatch algorithm proposed in the paper:

- "FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence" by Kihyuk Sohn, David Berthelot, Chun-Liang Li, Zizhao Zhang, Nicholas Carlini, Ekin D. Cubuk, Alex Kurakin, Han Zhang, Colin Raffel.
