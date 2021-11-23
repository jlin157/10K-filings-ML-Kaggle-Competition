# 10K-filings-ML-Kaggle-Competition

We have a set of 10k's and their respective sector labels. The goal is to train a model that can predict the sector of a company using only the text from its 10k filing.

10k_filings_train.csv

The train set. You will train your model of choice on this data. You can split this train set into a train and validation for hyperparameter tuning. The column you want to predict is the label column. There are 9 unique sectors, so this is a multiclass classification problem. The company sectors were identified from the SEC website. While there are many more detailed sectors (under "industry" column), in this task you only have to predict the high-level sector group. Only use the body of the 10K for features .

10k_filings_test_wo_labels.csv

The test set. The labels are omitted. Only submit your model's predicted sector for the test set
