# Credit-card-fault-detection
This project focuses on developing a machine learning system for credit card fraud detection using the Kaggle Credit Card Fraud Detection dataset. 

# Dataset : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This is a machine learning project that aims to detect fraudulent credit card transactions using a dataset from Kaggle. The dataset contains anonymized credit card transactions and labels indicating whether a transaction is fraudulent or not. 
The project includes the following steps:

# Data preprocessing: 
The dataset is loaded and preprocessed to remove missing values and scale the features. Principal Component Analysis (PCA) is also applied for dimensionality reduction.

# Balancing the dataset: 
The dataset is highly imbalanced, with only 0.172% of the transactions being fraudulent. The imbalanced dataset is balanced using Synthetic Minority Over-sampling Technique (SMOTE) to create a balanced dataset for training the machine learning model.

# Machine learning model: 
Logistic Regression is used as the machine learning algorithm to detect fraudulent transactions. The model is trained on the balanced dataset and evaluated using various metrics such as accuracy, precision, recall, and F1-score.

# Requirements:
Python 3.x
Jupyter Notebook
Scikit-learn
Pandas
NumPy
Matplotlib

# Credits
Kaggle Credit Card Fraud Detection dataset: https://www.kaggle.com/mlg-ulb/creditcardfraud
Scikit-learn library for machine learning in Python: https://scikit-learn.org/stable/
Flask web framework for Python: https://flask.palletsprojects.com/en/2.1.x/
Heroku cloud platform for deploying web applications: https://www.heroku.com/
Matplotlib library for data visualization in Python: https://matplotlib.org/
Pandas library for data manipulation in Python: https://pandas.pydata.org/

# License
This project is licensed under the MIT License.
