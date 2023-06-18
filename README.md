# Hyperspectral Image Classification with HybridSN

This repository contains the implementation of the "HybridSN" algorithm for hyperspectral image classification, as proposed by S. K. Roy, G. Krishna, S. R. Dubey, and B. B. Chaudhuri in their paper titled "HybridSN: Exploring 3-D–2-D CNN Feature Hierarchy for Hyperspectral Image Classification," published in IEEE Geoscience and Remote Sensing Letters.

## Introduction

Hyperspectral imaging combines spatial and spectral information of the ground to enable accurate classification of different land cover types. The "HybridSN" algorithm leverages a hybrid architecture consisting of 3-D and 2-D convolutional neural networks (CNNs) to capture both the spatial and spectral features in hyperspectral images, improving classification performance.

## Datasets

We have evaluated the "HybridSN" algorithm on three benchmark hyperspectral datasets:

1. Indian Pines
2. Pavia University
3. Salinas

Each dataset provides spatial and spectral information of the ground, allowing us to train and test the classification model effectively.

## Implementation Details

The implementation of the "HybridSN" algorithm is provided in this repository. Here are the key components and steps involved:

1. Preprocessing: The hyperspectral datasets are preprocessed to remove noise, normalize spectral bands, and handle class imbalance if necessary.

2. Network Architecture: The "HybridSN" algorithm consists of a 3-D CNN followed by a 2-D CNN. The 3-D CNN captures spectral-spatial features, while the 2-D CNN further refines the learned representations.

3. Training and Evaluation: The model is trained using labeled samples from the hyperspectral datasets. We utilize standard evaluation metrics such as accuracy, precision, recall, and F1-score to assess the performance of the algorithm.

## Usage

To use the "HybridSN" algorithm for hyperspectral image classification:

## Results
The results of applying the "HybridSN" algorithm on the Indian Pines, Pavia University, and Salinas datasets are summarized below:

1. Indian Pines: Overall accuracy of 99.72%, with 0.99 class-wise precision, recall, and F1-score detailed in the classification report.

2. Pavia University: Achieved an overall accuracy of 99.99%, with 1.00 class-wise performance metrics provided in the classification report.

3. Salinas: Attained an overall accuracy of 99.38%, along with class-wise precision, recall, and F1-score in the classification report.

For more detailed information on the results and performance metrics, please refer to the corresponding results figures and classification reports in the repository.

## Citation
here the implemented "HybridSN" algorithm is proposed in the mentioned research paper:

S. K. Roy, G. Krishna, S. R. Dubey, and B. B. Chaudhuri, "HybridSN: Exploring 3-D–2-D CNN Feature Hierarchy for Hyperspectral Image Classification," in IEEE Geoscience and Remote Sensing Letters.[Link to the paper]([https://www.example.com/paper](https://ieeexplore.ieee.org/document/8736016))
