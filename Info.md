# The-three-Fs-of-online-banking-Fabricated-Financial-Fraud
Synthetic Financial Fraud Detection Using R

### Anomaly Detection for Fraudulent Transactions

Paysim synthetic dataset of mobile money transactions. Each step represents an hour of simulation. This dataset is scaled down 1/4 of the original dataset which is presented in the paper "PaySim: A financial mobile money simulator for fraud detection".
We present a synthetic dataset generated using the simulator called PaySim as an approach to such a problem. PaySim uses aggregated data from the private dataset to generate a synthetic dataset that resembles the normal operation of transactions and injects malicious behaviour to later evaluate the performance of fraud detection methods.

### DATASET DICTIONARY

*	step - Maps a unit of time in the real world. In this case 1 step is 1 hour of time.
*	type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER
*	amount - amount of the transaction in local currency
*	nameOrig - customer who started the transaction
*	oldbalanceOrg - initial balance before the transaction
*	newbalanceOrig - customer's balance after the transaction.
*	nameDest - recipient ID of the transaction.
*	oldbalanceDest - initial recipient balance before the transaction.
*	newbalanceDest - recipient's balance after the transaction.
*	isFraud - identifies a fraudulent transaction (1) and non fraudulent (0)
*	isFlaggedFraud - flags illegal attempts to transfer more than 200.000 in a single transaction.

### PROBLEM STATEMENT
##### How can we regulate in case the attribute "isFlaggedFraud" gets set or not ?
