# Customer Churn Prediction

This project aims to predict customer churn for a telecom company using machine learning. It leverages a dataset containing customer demographics, service usage, and churn status.

## Project Overview

Customer churn, also known as customer attrition, is a major concern for businesses across various industries. It refers to the phenomenon of customers discontinuing their relationship with a company. This project focuses on building a predictive model to identify customers who are likely to churn, enabling the telecom company to take proactive measures to retain them.

## Dataset

The project utilizes the Telco Customer Churn dataset, which includes information about customers' demographics, services subscribed, account information, and churn status. The dataset contains 7043 rows and 21 columns.

## Methodology

The following steps were undertaken in this project:

1. **Data Loading and Understanding:** The dataset was loaded into a pandas DataFrame, and exploratory data analysis was performed to gain insights into the data.
2. **Data Preprocessing:** Missing values were handled, categorical features were encoded, and the dataset was split into training and testing sets.
3. **Model Training:** Various machine learning models, including Decision Tree, Random Forest, and XGBoost, were trained on the preprocessed data. SMOTE was applied to balance the target variable.
4. **Model Evaluation:** The trained models were evaluated using metrics such as accuracy, precision, recall, and F1-score.
5. **Model Selection:** The Random Forest model was selected as the final model based on its performance on the test set.
6. **Predictive System:** A predictive system was built using the trained Random Forest model to predict churn for new customers.

## Results

The Random Forest model achieved an accuracy of approximately 80% on the test set. This indicates that the model can effectively predict customer churn with a reasonable level of accuracy.

## Usage

To use the predictive system, follow these steps:

1. Clone this repository to your local machine.
2. Install the required libraries listed in the `requirements.txt` file.
3. Run the `prediction.py` script, providing the input data for a new customer.
4. The script will output
