# **Customer Churn Prediction** 
This Jupyter notebook aims to evaluate a Customer churn dataset, its triggers and the main features which impact in customer churn in a telecommunications provider.

# 1. Installation
The Python version was updated to Python 3.8.5 here. And other modules and functions were used like:
-sklearn.preprocessing > MinMaxScaler
-sklearn.linear_model > LogisticRegression
-sklearn.model_selection > train_test_split
-sklearn.metrics > confusion_matrix
-seaborn
-awswrangler

# 2. Project Motivation
This project is part of a selective process of Clin/Devexo data scientist position. The challenge was given to solve a Kaggle competion from 2020. The goal was to implement and visualize stats and inferences from the customer churn dataset of a telecom provider in USA.

# 4. How To Interact With Your Project 
Methodology - CRISP-DM:
    The followed steps were used to infer the answer the proposed problem of churn in the Kaggle dataset proposed by Clin/Devexo company to its selective process. 

    1. Business Understanding:
        Why people from this telecom provider churns?
        Is there some state influence in churn?
        What are the main feature of influence?
    2. Data Undertanding:
        Data of customer churn from a USA telecom provider. 
    3. Data preparation:
        Evaluation of features to drop, add or prepare the data to answer the above questions.
 
    4. Prediction Model 
        It was used a Logistical Regression model. This part is still being implemented.
        
    5. Model Evaluation 
        This part is still being implemented.
    

# 5. Results
   The results obtined untill now showed that the disbalanced training datased probabily resulted in a model with overfitting. Future implementations and balancing of the data will be done to improve the model building. 

# 4. Licensing, Authors, Acknowledgments  
I would like to thank to Kaggle for providing the dataset used in this project and it can be originally find in a Kaggle 2020 competition [here](https://www.kaggle.com/c/customer-churn-prediction-2020/overview).