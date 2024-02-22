# KannadaMNIST

**Kannada MNIST Classification Project**
Overview
This project aims to solve a 10-class classification problem using the Kannada MNIST dataset. The dataset contains handwritten Kannada digits, and the goal is to classify them into respective classes.

Steps to Reproduce

1. Data Preparation
Download the dataset from Kaggle.
Upload the dataset file (.npz) to your Google Drive.

2. Google Colab Setup
Open the Jupyter Notebook (Kannada_MNIST_Classification.ipynb) using Google Colab.
Mount Google Drive to access the dataset file.

4. Data Processing
Extract the dataset from the npz file.
Perform PCA to reduce dimensionality to 10 components.

5. Model Training
Train the following models:
Decision Trees
Random Forest
Naive Bayes
K-NN Classifier

SVM
5. Evaluation
Evaluate each model using metrics:
Precision, Recall, F1-Score
Confusion Matrix
RoC - AUC Curve

6. Experimentation
Repeat the experiment for different component sizes: 15, 20, 25, 30.

Instructions for Google Colab Execution

Open the provided Jupyter Notebook in Google Colab.
Mount your Google Drive to access the dataset file.
Execute the cells step by step to process data, train models, and evaluate results.
