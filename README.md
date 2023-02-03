# Hexart.In-Task1
Online Fraud Detection using machine learning

This is a machine learning model built on logistic regression which can predict the anomaly of a transaction with ~99.97% accuracy

The Dataset used is a synthetic dataset generated using the simulator called PaySim as an approach to such a problem.
PaySim uses aggregated data from the private dataset to generate a synthetic dataset that resembles the normal 
operation of transactions and injects malicious behaviour to later evaluate the performance of fraud detection methods.

step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. 

type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

amount - amount of the transaction done in local currency.

nameOrig - name of the customer who started the transaction

oldbalanceOrg - initial balance before the transaction

newbalanceOrig - customer's balance after the transaction.

nameDest - recipient ID of the transaction.

oldbalanceDest - initial recipient balance before the transaction.

newbalanceDest - recipient's balance after the transaction.

isFraud - identifies a fraudulent transaction (1) and non fraudulent (0)

isFlaggedFraud - flags illegal attempts to transfer more than 200.000 in a single transaction.
