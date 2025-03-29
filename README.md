# EL4013 : Programming with Data (Python Coursework Project) created by: Asad Ali
# Student ID : G21111398
#Project Description:
##Project Overview
The Online Payment Fraud Detection System is an advanced cybersecurity solution designed to identify and prevent fraudulent activities in online transactions. With the increasing prevalence of online payment platforms, ensuring the security of financial transactions has become a critical concern. This project aims to leverage machine learning and data analytics techniques to develop a robust fraud detection system for online payment systems.

##Key Features:

1.   Real-time Monitoring: Continuous analysis of transactions for anomalies.
2.   Machine Learning Models: Implement predictive models for fraud identification.
3. Feature Engineering: Extract and use relevant transaction data features.

##Dataset Description
Limited access to public datasets poses a challenge, particularly in the burgeoning field of mobile money transactions within the financial services domain. Researchers, including our team focusing on fraud detection, face difficulties due to the inherent privacy associated with financial transactions, resulting in a scarcity of publicly accessible datasets.

This dataset is created using PaySim. PaySim serves as a mobile money transaction simulator, generated from a subset of actual transactions derived from a month's worth of financial logs from a mobile money service operating in an African nation. The original logs were supplied by a multinational company, a key player in the mobile financial service sector, presently operational in over 14 countries globally.

##Overview of Dataset
This is a sample of 1 row with headers explanation:

1,PAYMENT,1060.31,C429214117,1089.0,28.69,M1591654462,0.0,0.0,0,0

step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

amount - amount of the transaction in local currency.

nameOrig - customer who started the transaction

oldbalanceOrg - initial balance of sender before the transaction.

newbalanceOrig - new balance of sender after the transaction.

nameDest - customer who is the recipient of the transaction.

newbalanceDest - new balance of recipient after the transaction.

isFraud - The "isFraud" label in this dataset denotes transactions initiated by fraudulent agents within the simulation. In this context, fraudulent behavior involves attempting to gain unauthorized access to customer accounts with the goal of siphoning funds. This is achieved by transferring funds to another account and subsequently cashing out of the system.

isFlaggedFraud - isFlaggedFraud signifies a business strategy aimed at monitoring substantial transfers between accounts. This flag is activated in response to attempts that are deemed illegal or suspicious within the system.

# Research Question:
## With increase in emerging fraud techniques, How well does the fraud detection system adapt to these emerging fraud techniques and evolve with them in the rapidly changing landscape of online payment security? if not, how to improve the model to adapt to emerging fraud techniques?

Link for dataset is:
https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection

**This notebook file is created using Google Colab. You can run this file in Jupyter as well. For running this file in jupyter notebook, make sure the dataset is uploaded in the same directory where the notebook file is stored. You don't need to mount Google Drive if you are using jupyter notebook.**
