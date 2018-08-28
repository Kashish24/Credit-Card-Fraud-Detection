# Credit-Card-Fraud-Detection
Problem Statement: we need to help the Credit Card companies that must be able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
Dataset Description: 
The datasets contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we are not provided by the original features and more background information about the data. Features V1, V2, .…, V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
Inspiration: 
Identify fraudulent credit card transactions.
Given the class imbalance ratio, we are recommend to measure the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.
Acknowledgement: 
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.
Other Similar kinds of problems: Telecommunication fraud detection, Network intrusion detection, Fraud detection.
