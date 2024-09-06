# ANN Customer Chrun Classification

Streamlit App - https://e2e-ann-churn-classification.streamlit.app/

## About Dataset
The dataset used - 'Churn_Modelling.csv' contains mock customers data for a bank.
The target column is 'Exited' - denoted if a customer left the bank services or not, based on a number of different features
Our goal is to predict if as customer will leave the bank given certain input features.

## Transformations Used
Label Encoder and One Hot Encoders for categorical features

Standard Scaler to scale the training and test sets

## ANN Training
Inputs - 12

Dense layer (Hidden Layer 1) - 64

Dense layer (Hidden Layer 2) - 32

Output layer -1

Optimizer - Adam

Early Stopping and Tensorboard used

## Prediction
Import the saved pickle files - for encoders, scalers and model itself

Apply on input data and get prediction



