# Credit Card Fraud Detection

Detect fraudulent credit card transactions using machine learning and anomaly detection.



## Overview

This project analyzes credit card transactions to identify fraudulent behavior. The workflow demonstrates a full data science pipeline from preprocessing to model evaluation and visualization.

Note: The dataset is not included in this repository due to size limits.
You can download it here: <https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud>
Key steps include:


- Data loading and cleaning  

- Exploratory Data Analysis (EDA) and visualizations  

- Feature scaling and preprocessing  

- Anomaly detection using Isolation Forest  

- Supervised classification using Random Forest  

- Model evaluation with confusion matrices, ROC-AUC, and classification reports  

- Feature importance analysis to understand fraud drivers





---



## Key Steps Performed



&nbsp;**Data Preprocessing**

&nbsp;  - Scaled features and separated features from target  

&nbsp;  - Handled class imbalance  



&nbsp;**Exploratory Data Analysis**

&nbsp;  - Visualized transaction distributions and class imbalance  

&nbsp;  - Identified patterns and anomalies in the dataset  



&nbsp;**Modeling**

&nbsp;  - Applied Isolation Forest for unsupervised anomaly detection  

&nbsp;  - Trained Random Forest for supervised classification  



&nbsp;**Evaluation**

&nbsp;  - Used classification reports, confusion matrices, and ROC-AUC metrics  

&nbsp;  - Visualized feature importance to identify key fraud drivers  


---



## Results Summary

- Successfully detected fraudulent transactions using both unsupervised and supervised approaches  

- Isolation Forest captured anomalies, while Random Forest improved classification performance  

- Key features include transaction amount, time, and PCA-transformed components  



---



## Future Work

- Hyperparameter tuning and ensemble models for improved performance  

- Experiment with One-Class SVM, XGBoost, or deep learning methods  

- Deploy a real-time fraud detection system for financial institutions  



---


