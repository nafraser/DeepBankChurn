# DeepBankChurn

## Purpose

This notebook is for investigating the use of an ANN, specifically for a classification model where the dependent variable is imbalanced. The notebook uses the same BankChurners.csv used in the BankChurn [notebook](https://github.com/nafraser/BankChurn) and is guided by a Tensorflow [Tutorial](https://www.tensorflow.org/tutorials/structured_data/imbalanced_data). Also, currently I'm training the model using non-categorical variables only. While the original BankChurn has many dummy variables, ATM this notebook drops them.  It is a work in progress as I learn more.  

## Business Context

The Thera bank recently saw a steep decline in the number of users of their credit card, credit cards are a good source of income for banks because of different kinds of fees charged by the banks like annual fees, balance transfer fees, and cash advance fees, late payment fees, foreign transaction fees, and others. Some fees are charged to every user irrespective of usage, while others are charged under specified circumstances.

Customers’ leaving credit cards services would lead bank to loss, so the bank wants to analyze the data of customers and identify the customers who will leave their credit card services and reason for same – so that bank could improve upon those areas You as a Data scientist at Thera bank need to come up with a classification model that will help the bank improve its services so that customers do not renounce their credit cards