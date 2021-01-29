# Fraud Detection

An ongoing credit card fraud detection dataset exploration (via Kaggle).

## Dataset
The dataset for this project was downloaded from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud/data). The (creditcard.csv file) dataset contains transactions made by credit cards in September 2013 by european cardholders. The dataset presents transactions that occurred in two days, containing 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. 

The DS only contains numerical input variables which are the result of a PCA transformation. 
- V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
- 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
- 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. 
- 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise. 
