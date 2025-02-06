Leukemia Detection Using Convolutional Neural Networks

By Jumana Lightwala

Overview

This project presents a deep learning-based approach for detecting leukemia using Convolutional Neural Networks (CNNs). The goal is to develop an automated system that classifies leukemia cell images with high accuracy. Three CNN models were designed and evaluated, demonstrating the potential for effective leukemia detection.

Dataset

Source: Kaggle (Mehradaria - Leukemia Detection Dataset)

Classes: Benign, Early Pre-B, Pre-B, Pro-B

Preprocessing: Images resized to 224x224 pixels, normalized, and augmented (rotations, shifts, flips)

Model Architectures

Three CNN models were implemented:

Original Model: A baseline CNN with convolutional and max-pooling layers, followed by fully connected layers.

Segmented Model: A modified version of the original model for improved feature extraction.

Combined Model: A hybrid model combining strengths from both previous architectures.

Training Process

Optimizer: Adam with an initial learning rate of 0.001

Regularization: Batch normalization, L2 regularization, dropout layers

Learning Rate Adjustment: ReduceLROnPlateau to optimize learning rate

Early Stopping: Stops training when validation loss stagnates

Results

Original Model: Training Accuracy: 99.99%, Validation Accuracy: 95.84%

Segmented Model: Training Accuracy: ~100%, Validation Accuracy: ~85%

Combined Model: Training Accuracy: ~100%, Validation Accuracy: ~90%

Performance Comparison: The Combined Model achieved the best stability and accuracy.

Visualizations

Training and Validation Curves: Plots for accuracy and loss trends across models.

Sample Predictions: Demonstrates model effectiveness.

Correlation Matrix: Evaluates prediction similarities across models.

Conclusion

The proposed CNN models effectively classify leukemia cell images, showcasing their potential in aiding early diagnosis. Future work will focus on enhancing model performance using techniques like transfer learning and optimizing architectures.
