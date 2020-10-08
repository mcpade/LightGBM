# LightGBM
Using the Machine Learning LightGBM algorithm

The use of the LightGBM algorithm for a classification problem and for a regression problem is shown in this project

### LightGBM - Clasificación - Predict customer churn in banks

We start from the **Churn_Modelling.csv** dataset that contains data from bank clients collected during 6 months. The last column of the "Exited" dataset is our target column and its values are:
- 1: indicates that the customer left the bank
- 0: indicates that the customer remains in the bank

Objective: Machine learning model that is capable of predicting whether a customer is going to leave the bank or not. We are going to use the LightGBM model for this

Code: lightgradientboosting.ipynb

### LightGBM - Regression - Airbnb Price Prediction

We start from the clean csv files generated in the final bootcamp project. This LightGBM algorithm was not tested in the Machine Learning part so we are going to test it here. It starts from the files **listings_train.csv** and **listings_test.csv**
For calculation power issues in this case I have used Google Colaboratory

Code: LightGBM Regression Modeling - ML.ipynb

The tests have been carried out with only a few hyperparameters to verify their operation. This algorithm has more than 100 hyperparameters to test.

Documentation: https://lightgbm.readthedocs.io/en/latest/Parameters.html

