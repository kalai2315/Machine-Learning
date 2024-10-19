

**LDA (Linear Discriminant Analysis) on Digits Dataset** 

**Overview**

This project implements Linear Discriminant Analysis (LDA) for dimensionality reduction and classification on the load_digits dataset from scikit-learn. The project aims to demonstrate how to scale data, apply LDA, visualize the results, and classify the reduced data using Random Forest Classifier.

The load_digits dataset contains images of handwritten digits (0-9) represented as an 8x8 matrix of pixel values, with each image consisting of 64 features. The goal is to reduce these 64 features to a lower dimensional space (in this case, two components) using LDA, while preserving as much class-discriminating information as possible.

**Project Features**

**Data Preprocessing:**

Standardizing the features using StandardScaler.

Splitting the dataset into training and test sets.

**Dimensionality Reduction using LDA:**

LDA is applied to reduce the feature space to two components.

Visualize both the original high-dimensional data and the reduced data after LDA.

**Random Forest Classifier:**

Train a Random Forest model on the LDA-transformed data.

Evaluate the model's performance using accuracy, confusion matrix, and classification report.

**Visualization:**

Plot the original data (before applying LDA).

Visualize the transformed data after LDA in 2D space, where classes are better separated.

