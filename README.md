# Classification Challenge
This project implements a spam detection system for an Internet Service Provider to improve the email filtering system for its customers. I have been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. This model accurately detects spam emails.

## Functions:
## Data Preprocessing
- Features (`X`) and labels (`y`) are separated.
- Split the data into training and testing sets.
- Scale the features using `StandardScaler`.
## Model Training
- Create a Logistic Regression model.
- Create a Random Forest model.
## Model Evaluation
- Predictions on the test data are made.
- Accuracy scores for both models are calculated.
- The Random Forest Classifier outperformed the Logistic Regression model (Random Forest Classifier accuracy is 96.70% Vs. the Logistic Regression model accuracy is 92.88%).

## Summary
This README provides a detailed overview of the spam detection project and results. The Random Forest Classifier achieved a higher accuracy rate in detecting spam emails compared to the Logistic Regression model.
