# Bank-Customer-Churn-Prediction

![image](https://user-images.githubusercontent.com/58620359/174948746-5dc3418a-8296-4cc8-9561-f8f12ca9a0a4.png)

## Problem Statement :

Customer churn or customer attrition is a tendency of clients or customers to abandon a brand and stop being a paying client of a particular business or organization. The percentage of customers that discontinue using a company’s services or products during a specific period is called a customer churn rate. Several bad experiences (or just one) are enough, and a customer may quit. And if a large chunk of unsatisfied customers churn at a time interval, both material losses and damage to reputation would be enormous.

A reputed bank “ABC BANK” wants to predict the Churn rate. Create a model by using different machine learning approaches that can predict the best result. 

## Dataset Description :

This is a public dataset, The dataset format is given below.
 
Inside the dataset, there are 10000 rows and 14 different columns.

The target column here is **Exited** here.

Click [here](https://www.kaggle.com/datasets/louishgy/churn-modelling?select=Churn_Modelling.csv) to download the dataset.

The details about all the columns are given in the following data dictionary -

| Variable | Definition |
| ------------- | ------------- |
| RowNumber | Unique Row Number |
| CustomerId | Unique Customer Id |
| Surname | Surname of a customer |
| CreditScore | Credit Score of each Customer  |
| Geography | Geographical Location of Customers |
| City_Category | Category of the City (A,B,C) |
| Gender | Sex of Customers |
| Age | Age of Each Customer |
| Tenure | Number of years |
| Balance | Current Balance of Customers |
| NumOfProducts | Number of Products |
| HasCrCard | If a customer has a credit card or not |
| IsActiveMember | If a customer is active or not |
| EstimatedSalary | Estimated Salary of each Customer |
| **Exited** | **Customer left the bank or Not (Target Variable)** |

## Working Flow :
In order to create a model these are the following procedure - 

- Split the dataset in 70% of Train set and 30% of Test Set
- Feature engineering 
- Check the accuracy score for both Training and Test Set
- Compare the accuracies for both Training and Test set, in order to check for the overfitting issues 
