# **CUSTOMER CHURN PREDICTION**
This project aims to predict whether a customer is likely to leave a service, based on various account related features. Accurately identifying customers at risk of churning can help businesses take proactive steps to retain them

## Problem Statement
Customer churn refers to the situation where customers leave a business or service.
The objective of this project is to build a machine learning model that can predict whether a customer will leave.

## Dataset
The dataset used in this project can be found [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).It contains information about Telco customers including demographics, service subscriptions, and customer churn status. 

## Project goals
The primary objectives of this project are:
1. Perform exploratory data analysis(EDA) to understand key churn drivers
2. Preprocess and clean the data
3. Compare multiple classification algorithms
4. Hyperparameter Tuning
5. Evaluate model perfomance

## Tools and Technologies
- **Python**
- **Pandas** and **Numpy**
- **Matplotlib** and **Seaborn**
- **XGBoost**, **RandomForest**, **SVM**, **KNN**
- **Jupyter Notebook**

  ## Models used
  The following models were trained and compared
  
| Model               | Train Accuracy | Test Accuracy |
|--------------------|----------------|---------------|
| Logistic Regression| 0.799          | 0.814         |
| Naive Bayes        | 0.657          | 0.667         |
| SVM                | 0.734          | 0.735         |
| XGBoost            | 0.928          | 0.786         |
| Random Forest      | 0.998          | 0.792         |
| KNN                | 0.826          | 0.782         |

**Logistic Regression** gave the most balanced results, while XGBoost and RandomForest showed signs of overfitting

## Insights
- Senior citizens had a higher churn rate compared to younger customers
- Customers with no dependents and partners were more likely to churn
- Customers who churn tend to have low tenure(Used the service for a short period of time)
- Customers with Multiple lines have a slightly higher churn rate
- Customers who don't stream movies and tv have a slightly higher churn rate
- Customers who churn are under month to month contract
- Customers using Fiber optic internet churned more compared to DSL users

 ## Author
 Mathenge Leah
