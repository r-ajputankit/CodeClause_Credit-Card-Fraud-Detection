# Credit-Card-Fraud-Detection

## Introduction
The Credit Card Fraud Detection project aims to build a machine learning model that can accurately detect fraudulent credit card transactions. Credit card fraud is a significant concern for both financial institutions and their customers. Detecting fraudulent activities in real-time can help prevent unauthorized transactions and protect customers from financial losses.

In this project, we will develop and evaluate a machine learning model to classify credit card transactions as either legitimate or fraudulent based on historical transaction data. The model will be trained on labeled data to learn patterns associated with fraudulent behavior.

## Dataset
The dataset used for this project contains historical credit card transactions, where each transaction is labeled as fraudulent (positive class) or legitimate (negative class). The dataset should be divided into training and testing sets to evaluate the model's performance.
(The Dataset is downloaded from Kaggle.com)

## Installation
To set up the project environment, follow these steps:

1. Clone the repository to your local machine.

        git clone https://github.com/your-username/credit-card-fraud-detection.git
        cd credit-card-fraud-detection

2. Create a virtual environment

        python -m venv <env name>        # creating the virtual environment
        .\<env name>\Scripts\activate    # activate environment

3. Install the required dependencies.

        pip install -r requirements.txt

4. Now open jupyter notebook
 
        jupyter notebbok
5. run the credit card fraud Detection.ipynb first, then use the model


## Model
For the credit card fraud detection model, we will use a machine learning algorithm "Logistic Regression"
(Other algorithms which can be used-Random Forest, or Gradient Boosting).

The model will be trained on the labeled training dataset (Supervised Learning). After training, the model will be saved so that it can be used for predictions on new data.

Note: the model has been trained with values of the features.

## Evaluation
The evaluation is done with following-
    1. Accuracy test
    2. mean squared error

## Conclusion
The Credit Card Fraud Detection project provides a solution to identify and prevent fraudulent credit card transactions. By using machine learning algorithms and evaluating their performance, we can develop an effective fraud detection system that safeguards customers and financial institutions.
