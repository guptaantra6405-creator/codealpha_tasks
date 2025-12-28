# CodeAlpha_IrisFlowerClassification
A machine learning classification project using Decision Tree to predict Iris flower species with performance evaluation and overfitting control.
# Iris Flower Classification

This repository contains a machine learning project developed as part of the **CodeAlpha Data Science Internship**.

## Objective
The objective of this project is to build and evaluate a machine learning model capable of classifying Iris flower species based on sepal and petal measurements.

## Dataset
The Iris dataset consists of 150 samples and includes the following numerical features:
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm

**Target Variable:**
- Species (Iris-setosa, Iris-versicolor, Iris-virginica)

## Methodology
The project follows a complete machine learning workflow:
1. Data loading and preprocessing
2. Feature–target separation
3. Label encoding of the target variable
4. Model training using Decision Tree Classifier
5. Model evaluation using accuracy and F1-score
6. Overfitting analysis through depth tuning and cross-validation
7. Feature importance analysis

## Model and Evaluation
- Algorithm: Decision Tree Classifier
- Accuracy: ~100%
- Weighted F1-Score: ~1.0

## Overfitting Control
To reduce overfitting, the model was trained with varying tree depths.  
A maximum depth of **3** was found to provide the best balance between training accuracy and cross-validation performance.

## Feature Importance
Feature importance analysis indicates that **Petal Length** and **Petal Width** are the most significant features for classifying Iris flower species.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Project Structure
CodeAlpha_IrisFlowerClassification
├── iris_flower_classification.ipynb
├── README.md
├── requirements.txt
└── iris_flower_classification.py


## Author
**Antra Gupta**

