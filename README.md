# Credit-Card-Fraud-Detection

## Dataset

The datasets contains transactions made by credit cards in September 2013 by european cardholders. 
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.  

## Approach
In this kernel for dealing with the imbalanced data set we use the oversampling approach and use SMOT.
SMOTE (synthetic minority oversampling technique) is one of the most commonly used oversampling methods to solve the imbalance problem. It aims to balance class distribution by randomly increasing minority class examples by replicating them. 
We use grid search to fit and find the best parameters for the logistic regression model to see how accurate they are in detecting whether a transaction is a normal payment or a fraud. 
