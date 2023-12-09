# bank_churn_modelling-ML-5006

# Project Title: Customer Churn Prediction in Banking

# Description:
This project focuses on predicting customer churn in banking. Using a comprehensive dataset, the study aims to explore and cluster data through visualization, statistical analysis, and principal component analysis. The goal is to develop a classification model that accurately predicts whether customers will continue their relationship with the bank or switch to another institution.

# Dataset:
The dataset, titled "Churn_Modelling.csv", contains the following columns:
1. RowNumber: Row number (to be removed).
2. CustomerID: Random and unique values (to be removed).
3. Surname: Customer's surname (to be removed).
4. CreditScore: Score showing customer's credit behavior.
5. Geography: Customer’s location.
6. Gender: Customer’s gender.
7. Age Customer’s age.
8. Tenure: Number of years as a bank customer.
9. Balance: Customer's account balance.
10. NumOfProducts: Number of products purchased from the bank.
11. HasCrCard: Whether the customer has a credit card (0=No, 1=Yes).
12. IsActiveMember: Active status of the customer (0=No, 1=Yes).
13. EstimatedSalary: Customer's estimated salary.
14. Exited: Indicates churn (0=No, 1=Yes).

# Project Structure:
1. Introduction and Scope: Define the purpose and scope of the project.
2. Data Cleaning and Preparation:
   - Remove irrelevant columns (RowNumber, CustomerID, Surname).
   - Handle missing values and outliers.
   - Standardize and normalize data where necessary.
3. Data Exploration and Visualization:
   - Analyze the distribution of key features like Age, Geography, Balance.
   - Visualize relationships between features and customer churn.
4. Feature Engineering:
   - Derive new features if necessary.
   - Encode categorical variables.
5. Model Building:
   - Split data into training and testing sets.
   - Experiment with different models (e.g., logistic regression, decision trees, random forests).
   - Train models on the training set.
6. Model Evaluation and Selection:
   - Evaluate models using metrics like accuracy, precision, recall, F1 score.
   - Select the best-performing model.
7. Insights and Conclusion:
   - Interpret the model results.
   - Discuss factors influencing customer churn.
   - Provide recommendations based on findings.

This project outline will guide the development of a predictive model to identify the likelihood of bank customers discontinuing their services.
