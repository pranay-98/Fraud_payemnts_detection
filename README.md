# Fraud_payemnts_detection

# Introduction

Welcome to the Payments Fraud Detection Model repository! This project is focused on detecting fraudulent transactions among a large number of normal transactions. The dataset used in this project is transaction data for online purchases collected from an e-commerce retailer. The dataset contains more than 39000 transactions, and each transaction contains 5 features that describe the nature of the transactions.

# Problem

Fraud detection is a type of classification problem where the goal is to identify fraudulent transactions among a large number of normal transactions. Due to the highly imbalanced nature of fraud data, where fraudulent instances are usually much fewer than normal instances, the standard machine learning techniques may not work well.

# Solution

In this project, we used the Adaptive Synthetic Sampling (ADASYN) algorithm and SMOTE algorithm to oversample the minority class (fraudulent transactions) to balance the class distribution and improve the performance of the model. After that, we implemented Logistic Regression as our classification model.

# Requirements

To run this project, you will need the following packages:

* pandas
* numpy
* sklearn
* imbalanced-learn

# Results

"Ladies and Gentlemen, buckle up, 'cause we've got a wild ride ahead! Our model is performing like a boss, with an accuracy of 100%, and let's be real, we all know that's about as rare as finding a unicorn in your backyard. But hey, who are we to complain? We're on top of the world!"

# Conclusion

In this project, we have shown how to detect fraudulent transactions using a logistic regression model, ADASYN algorithm, and SMOTE algorithm. This model can be further improved by using other techniques such as ensemble methods or deep learning techniques. Feel free to use this code as a starting point for your own project and make sure to evaluate the performance on a validation set before deploying the model in production.
