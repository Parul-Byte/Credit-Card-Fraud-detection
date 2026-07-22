# Credit-Card-Fraud-Detection

 ## ABSTRACT
Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns that are indicative of fraudulent transactions. Credit card fraud refers to the physical loss of a credit card or the loss of sensitive credit card information. Many machinelearning algorithms can be used for detection. This project proposes to develop a machine-learning model to detect credit card fraud. The model will be trained on a dataset of historical credit card transactions and evaluated on a holdout dataset of unseen transactions.
<br>
<br>
<b>Keywords:</b> Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, K- Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.

<br>
<br>

## Overview

With the increase of people using credit cards in their daily lives, credit card companies should take special care of the security and safety of the customers. According to (Credit card statistics 2021), the number of people using credit cards worldwide was 2.8 billion in 2019; also, 70those users own a single card. Reports of Credit card fraud in the U.S. rose by 44.7in 2020. There are two kinds of credit card fraud, and the first is having a credit card account opened under your name by an identity thief. Reports of this fraudulent behaviour increased 48to 2020. The second type is when an identity thief uses an existing account you created, usually by stealing the
information on the credit card. Reports on this type of Fraud increased 9to 2020(Daly, 2021). Those statistics caught We’s attention as the numbers have increased drastically and rapidly throughout the years, which motivated We to resolve the issue analytically by using different machine learning methods to detect fraudulent credit card transactions within numerous transactions.

<br>
<br>

## Project goals

The main objectives of this project are:

- To develop machine learning models for credit card fraud detection.
- To analyze transaction patterns and classify fraudulent transactions.
- To compare different ML algorithms based on performance metrics.
- To identify the most effective model for fraud detection.

The models are evaluated using Accuracy, Precision, Recall, and F1-score.

<br>
<br>

## Data Source

The dataset was retrieved from an open-source website, Kaggle.com. 

The dataset contains credit card transactions made by European cardholders in 2013. It consists of:

- 284,807 transactions
- 31 attributes
- 28 anonymized features transformed using PCA
- Time feature
- Amount feature
- Class feature

The **Class** attribute represents the target variable:

- 0 → Normal Transaction
- 1 → Fraudulent Transaction
<br>
<br>
<b>Dataset: </b>
<a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">kaggle Dataset</a>

<br>
<br>


## Machine Learning Algorithms
1. Decision Tree (D.T.)
2. K-Nearest Neighbor (KNN) 
3. Logistic Regression (L.R.)
4. Support Vector Machine (SVM)


<br>
<br>


## Model Performance

The models were evaluated using Accuracy, Precision, Recall, and F1-score.

| Model | Accuracy | Precision | Recall | F1 Score |
|------|----------|-----------|--------|----------|
| Decision Tree | 1.00 | 0.83 | 0.81 | 0.82 |
| Logistic Regression | 0.91 | 0.94 | 0.87 | 0.90 |
| SVM | 0.95 | 0.99 | 0.86 | 0.92 |
| KNN | 1.00 | 0.83 | 0.82 | 0.83 |

<br>
<br>



## Results

Based on the evaluation metrics, Support Vector Machine achieved the highest F1-score and precision among the tested models.

Although Decision Tree and KNN achieved high accuracy, accuracy alone is not sufficient for fraud detection because the dataset is highly imbalanced. Therefore, F1-score and precision are considered important metrics for selecting the best model.

<br>
<br>



## Future Work 
There are many ways to improve the model, such as using it on different datasets with various sizes and data types or by changing the data splitting ratio and viewing it from a different algorithm perspective. An example can be merging telecom datato calculate the location of people to have better knowledge of the location of the card owner while his/her credit card is being used; this will ease the detection because if the card owner is in Dubai and a transaction of his card was made in Abu Dhabi, it
will easily be detected as Fraud.

<br>
<br>

## Conclusion
In conclusion, the main objective of this project was to find the most suited model for creditcard fraud detection in terms of the machine learning techniques chosen for the project. It was met by building the four models and finding the accuracies of them all; the best in terms of accuracy is KNN and Decision Tree, which scored 100 on credit card fraud and increased the customer’s satisfaction as it will provide themwith a better experience and feeling secure.
