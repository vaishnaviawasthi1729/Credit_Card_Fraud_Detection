**Credit Card Fraud Detection**
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset used is highly unbalanced, with the majority of transactions being legitimate. To address this imbalance, the dataset is under-sampled to create a balanced dataset, enabling the model to detect fraud effectively.


Credit card fraud is a significant issue for financial institutions. The goal of this project is to build a machine learning model that can accurately identify fraudulent transactions. The model is trained using Logistic Regression, a powerful statistical method used for binary classification tasks.

**Dataset Information**
Dataset used: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Number of Instances: 284,807
Number of Features: 30 (anonymized using PCA)
Class Labels:
0: Legitimate transaction
1: Fraudulent transaction
The dataset is highly unbalanced, with only 492 fraudulent transactions, which accounts for approximately 0.17% of all transactions.

**Installation**
To run the project locally, ensure you have Python installed. You can install the required dependencies by running:
pip install numpy pandas scikit-learn

**Usage**
Import Dependencies:

Import necessary libraries, including NumPy, pandas, scikit-learn.
Load Data:

Load the credit card dataset using pandas.
Examine the first and last few rows of the dataset to understand the structure.
Data Exploration:

Explore the data to understand the distribution of features and target labels.
Check for any missing values.
Data Preprocessing:

Separate the legitimate and fraudulent transactions.
Perform under-sampling to create a balanced dataset.
Model Training:

Split the data into features and target labels.
Train a Logistic Regression model using the balanced dataset.
Model Evaluation:

Evaluate the model using accuracy score and other metrics.
**Features and Implementation**
Under-Sampling: To handle the class imbalance, the legitimate transactions are under-sampled to match the number of fraudulent transactions.
Logistic Regression: Used to train the model for binary classification between legitimate and fraudulent transactions.
Data Analysis: Basic statistical analysis is performed on both legitimate and fraudulent transactions to understand their characteristics.

**Results**
The model is trained on an under-sampled dataset to handle the class imbalance. The Logistic Regression model is then evaluated for its accuracy in detecting fraudulent transactions.

**Contributing**
If you would like to contribute to this project, feel free to submit a pull request or raise an issue. Contributions are welcome!


