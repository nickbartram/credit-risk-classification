
# README for Module 20 Challenge (credit-risk-classification)

## Introduction

This challenge looks at credit risk classification and the status of loans. It uses a dataset containing the lending activity from a peer-to-peer lending service company. The challenge tries to identify the creditworthiness of borrowers. The challenge requires the use of supervised machine learning to identify clusters and make predictions.

## Data

The data consists of a CSV file (`lending_data.csv`) that contains data related to credit risk classification. It is a large CSV file with only over 7,000+ rows and 8 columns. Each row represents a different loan, and the columns contains values of each loan (e.g. size, interest rate, status).

## Methodology

Pandas is used to quickly read the data from the CSV file. The `scikit-learn` library is used throughout the challenge, specifically the functions `LogisticRegression` and `train_test_split`. These are used to split the data into training and testing aspects, as well as to actually train the data. Logistic regression is used to classify the data into either low or high risk loans.

## Results

The results are shown in a confusion matrix, as well as a classification report near the end of the challenge. It shows relatively high scores from accuracy, precision, recall, and f1 scores of the logistic regression (classification). The predictions for healthy (low-risk) loans was essentially perfect, however the high risk loan classification scored a little lower (around 90% f1 score). 

## Conclusion

Overall this was a fairly accurate predictive model. The logistic regression classified the loans reasonably well. It would be a good model for predicting healthy loans. It would perform slightly worse for high-risk loans. With an f1 score of 89%, most high-risk loans are predicted well. However there's a 1 in 10 chance that the model could be incorrect at predicting a high-risk loan, which could be frustrating for those potential borrowers.

## References

Class materials were used extensively for this assignment, as well as:

* stackoverflow.com
* Xpert Learning Assistant
* ChatGPT.com

## Usage

This `.ipynb` file should be easy to use. Hit `Run All` at the top of the file in VSCode and everything should run fine.
