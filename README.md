# ANN Classification for Customer Churn Prediction

This project focuses on building an Artificial Neural Network (ANN) from scratch to classify customer churn. The objective is to predict whether customers will leave a service based on their behavioral and demographic data.

## Table of Contents
Introduction,
Dataset,
Model Architecture,
Installation,
Usage,
Results,
Contributing,
License

### Introduction
Customer churn prediction is critical for businesses to retain customers and reduce revenue loss. This project implements a deep learning model using an ANN to classify customer churn based on various input features such as customer demographics, tenure, and service usage patterns.

Dataset:-
The dataset used for this project includes customer data with features like:

Customer ID, 
Gender, 
Tenure, 
Monthly Charges, 
Total Charges, 
Contract Type, 
Payment Method, 

Target Variable:-
Churn (Yes/No)

### Model Architecture
The ANN model consists of the following layers:

Input Layer:- Accepts input features from the dataset.
Hidden Layers:- Two fully connected layers with ReLU activation.
Output Layer:- A single neuron with a sigmoid activation function for binary classification.


