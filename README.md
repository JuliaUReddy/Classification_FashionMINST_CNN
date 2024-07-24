# Project Overview

This project focuses on addressing the overfitting issue encountered while classifying garment images with multiple classes. The objective is to enhance the performance of the Convolutional Neural Network (CNN) model used for this task.

## Key Goals
- **Overfit Issue**: Tackle the overfitting problem in garment image classification.
- **CNN Model Improvement**: Propose modifications to the existing CNN model to enhance its accuracy and robustness.

## CNN Model Enhancements
The CNN model in this project incorporates several key changes:
- **Batch Normalization**: Added to stabilize and accelerate training.
- **Dropout Layer**: Introduced to prevent overfitting and improve model generalization.

## Model Modifications
The following adjustments were made to the CNN model:
1. **Kernel Size**: Changed to `(3, 3)` for all convolutional layers.
2. **Activation Function**: Updated from ReLU to **LeakyReLU** to address the vanishing gradient problem.
3. **Data Augmentation**: Applied to enhance the diversity of training data and improve model performance.
4. **Architecture**: Integrated a **VGGNet-like architecture** to leverage deep learning features and improve classification accuracy.

## Dataset
The standard **FASHION-MNIST** dataset was used for training and evaluation.

## Results
The proposed modifications resulted in significant improvements in model performance. Details of the results and evaluations are included in the project documentation.
