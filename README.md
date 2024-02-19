# Flower Classification with TPU

## Overview
This project focuses on the classification of 104 flower types using advanced machine learning techniques and powerful Deep Learning models. By leveraging Tensor Processing Units (TPUs), the project achieves high efficiency in processing and accuracy in results. 
- **Data Augmentation**: Enhances the input dataset, providing a diverse set of training images.
- **Custom Learning Rate Scheduler**: Optimizes the learning process for better model performance.
- **Test Time Augmentation (TTA)**: Improves prediction accuracy by altering the input data during the testing phase.

## Models Used
- **Inception ResNet V2**
- **DenseNET 201**
- **Efficient NET B7**

The ensemble approach, combining DenseNET 201 and Efficient NET B7, showed the most promising results.

## Achievements
- **High Classification Accuracy**: Successfully classified 104 different types of flowers.
- **Optimal Performance**: Achieved an F1 score of 0.96464 with the ensemble model.
