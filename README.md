Students Annual Score Prediction using ANN


This project uses an Artificial Neural Network (ANN) to predict students' Annual Score based on their academic performance throughout the year. The dataset contains assessment scores from History and Geography subjects, along with student gender and final success status.


- Project Overview

The objective of this project is to build a regression model using an Artificial Neural Network (ANN) that predicts a student's Annual Score using continuous assessment and examination marks.


- The project demonstrates:

Data preprocessing.

Feature engineering.

Data normalization.

ANN model development using TensorFlow/Keras.

Model training and evaluation.

Prediction of annual scores.


-ANN Architecture
Example architecture:

Input Layer,
Dense Layer (64 neurons, ReLU),
Dense Layer (32 neurons, ReLU),
Dense Layer (16 neurons, ReLU),
Output Layer (1 neuron, Linear Activation).


- Objective:
Predict the Annual Score using:

Gender.

Test scores.

Exam scores.

The Success column can be used later for a classification task but is not the prediction target in this project.


This project was developed for educational purposes to demonstrate the application of Artificial Neural Networks (ANNs) for student performance prediction using History and Geography assessment data.




Customer Churn Prediction using Artificial Neural Network (ANN)


- Project Overview:

This project develops an Artificial Neural Network (ANN) to predict whether a customer is likely to leave (churn) or remain with a bank. Customer churn prediction is a critical business problem, enabling organizations to identify at-risk customers and implement retention strategies before they leave.

The model is trained on the Churn Modelling Dataset, which contains customer demographic information, account details, and banking behavior.


- Objective:

The primary objective of this project is to build a binary classification model that predicts the Exited status of a customer based on their personal and banking information.

Target Variable: Exited:

0: Customer remains with the bank.

1: Customer has left the bank (churned).


- Technologies Used:


Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

TensorFlow / Keras


- Project Workflow:

Load the dataset.

Data exploration and visualization.

Data preprocessing.

Remove unnecessary columns (Row Number, Customer Id, Surname).

Encode categorical variables (Gender, Geography).

Feature scaling using StandardScaler.

Split data into training and testing sets.

Build the ANN model.

Train the model.

Evaluate model performance.

Predict customer churn.


This project was developed for educational purposes to demonstrate the application of Artificial Neural Networks (ANNs) in predicting customer churn. The project showcases a complete machine learning workflow, including data preprocessing, feature engineering, ANN model development, training, evaluation, and prediction using the Churn Modelling dataset.
