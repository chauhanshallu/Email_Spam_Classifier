# Email Spam Classifier

## Overview

This project builds a machine learning-based Email Spam Classifier using the Logistic Regression algorithm. The classifier is trained to differentiate between spam and legitimate (ham) emails based on their textual content. The project leverages text feature extraction techniques and evaluates the model's performance using real-world examples.

## Key Features

- **Text Feature Extraction**: Used the TfidfVectorizer from Scikit-learn to convert email text data into numerical features suitable for model training.

- **Model Training and Prediction**:
  - Trained a Logistic Regression model to classify emails.
  - Evaluated the model's accuracy on both training and test datasets.

- **Real-time Email Classification**:
  - Provided examples of how to classify new emails as "spam" or "ham" using the trained model.

## Libraries and Tools Used

- **Programming Language**: Python
- **Libraries**:
  - numpy, pandas for data manipulation and analysis.
  - scikit-learn for machine learning, feature extraction, and model evaluation.

## Workflow

### 1. Data Preparation:

  - Split the dataset into training and testing sets using train_test_split.
  - Transformed email text data into TF-IDF features for numerical representation.

### 2. Model Training:

  - Trained a Logistic Regression model on the TF-IDF features from the training dataset.

### 3. Model Evaluation:

  - Measured the model's accuracy on both training and test datasets using accuracy_score.

### 4. Email Classification Examples:

  - Demonstrated the classification of sample emails as "spam" or "ham" using the trained model.

## Results

- The model achieved high accuracy on the test dataset, demonstrating its effectiveness in distinguishing between spam and legitimate emails.
