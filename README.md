# Sentimental_Analysis
This project focuses on building a machine learning-based classifier to analyze the "Stories" dataset and predict the classes associated with each story. The dataset contains stories with corresponding labels, and the goal is to develop a classifier that can accurately classify stories into their respective classes.

## 1. Data Loading and Preprocessing:
Load the "Stories" dataset containing stories with associated labels.
Preprocess the text data by tokenizing the stories and converting them to lowercase.

## 2. Feature Extraction using CountVectorizer:

Use CountVectorizer to convert the preprocessed text data into numerical features.
CountVectorizer creates a bag-of-words representation, capturing the frequency of each word in the stories.

## 3. Train-Test Split:

Split the dataset into training and test sets for model evaluation.
Use the last 20% of each file as the test set, and the remaining 80% as the training set to ensure a diverse test dataset.

## 4. Initializing SVM Classifier:

Select the SVM classifier (SVC) for text classification.
Define the classifier with a linear kernel to handle the high-dimensional text data effectively.

## 5. Training the SVM Classifier:

Fit the SVM classifier on the training data (X_train) and corresponding labels (y_train).
During training, the classifier learns the decision boundary to separate different classes based on the feature vectors.

## 6.Making Predictions:

Use the trained SVM classifier to make predictions on the test data (X_test).
Predictions are made for each story, assigning it to one of the predefined classes.

## 7. Performance Evaluation:

 - Calculate the accuracy, precision, recall, and F-score for each class and the overall test data.
 - Accuracy: The proportion of correctly classified instances to the total instances in the test set.
 - Precision: The ratio of true positive predictions to the total predicted positive instances for a specific class.
 - Recall: The ratio of true positive predictions to the total actual positive instances for a specific class.
 - F-score: The harmonic mean of precision and recall, providing a balanced measure of both metrics.
