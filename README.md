# bank-customer-behaviour-prediction
Overview
This repository contains the code and resources for building a predictive model to identify potential customers who are likely to subscribe to term deposits in a retail banking institution. The model aims to optimize telephonic marketing campaigns by targeting specific customers who are more likely to convert.

Problem Statement
The client, a retail banking institution, heavily relies on term deposits as a significant source of income. Term deposits involve a cash investment held at a financial institution for an agreed rate of interest over a fixed period. The bank employs various outreach plans, including email marketing, advertisements, telephonic marketing, and digital marketing. Telephonic marketing, while effective, requires substantial investment in large call centers. Thus, it is crucial to identify customers most likely to subscribe beforehand to optimize resources and target them specifically via call.

Data
The provided dataset (train.csv) contains client data, including age, job type, marital status, and information about the telephonic marketing call, such as call duration, day, and month. The target variable, "subscribed," indicates whether the client has subscribed to a term deposit.

Data Files:
train.csv: This dataset is used to train the predictive model and contains client and call details, along with the target variable "subscribed."

test.csv: After training the model, it can be used to predict whether a new set of clients in this dataset will subscribe to a term deposit.
