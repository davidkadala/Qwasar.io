# Welcome to My Paypal
Please note that this project was completed in Google Colab. Find the link to the notebook attached

## Task
This project involves developing a model to detect credit card fraud from a highly imbalanced dataset

## Description
The approach for solving this problem is as follows:
1. Collection and cleaning of dataset: the dataset was retrieved from my google drive. The dataset was cleaned of null values(which were absent)
Duplicated rows were however not removed in order not to affect an already imbalanced dataset.
2. Exploration and Visualisation: the dataset was explored to find the and visualise the class imbalance (99% to 0.1%) of non-fraud and fraud respectively.
Visualisation of the correlation matrix was also done. I also checked for the total amount lost to fraud, which was about $60,000 in two days.
3. Modeling: the data was preprocessed by scaling the numerical features 'Amount' and 'Time' using the StandardScaler(). SMOTE (Synthetic Minority Over-sampling
Technique) was used to deal with class imbalance.
Three models were trained and evaluated to find the best fit: Logistic regression, Random forest classifier and XGBoost classifier. Random forest and XGBoost performed
better, but Random forest stood out in the confusion matrix with less false positives. This model was then saved to pickle which will be further used for deployment

## Installation
The project is available on the google colab notebook. An API can be created and hosted on the cloud for proper implementation

## Usage
The project can be used either from the notebook or when deployed. From the notebook, financial data can be supplied to the trained model after preprocessing
and a prediction test run. The outcome can then be visualised.
```
Nil
```

### The Core Team
Project executed by David Kadala, Qwasar Team
<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
