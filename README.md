# Customer Churn Prediction and Attrition Analysis

This project focuses on analyzing and predicting customer attrition (churn) for a credit card company using machine learning and data visualization techniques. The dataset provided contains customer demographic information, financial data, and behavioral insights. The goal is to identify patterns in customer churn and build a predictive model to forecast attrition.

## Project Structure

- **Customer Attrition Analysis.pbix**: This Power BI report provides an in-depth analysis of customer demographics, financial habits, and behavioral trends related to customer attrition. It includes insights about customer segments more prone to churn.
  
- **model.ipynb**: A Jupyter notebook that contains the end-to-end machine learning pipeline. This includes data preprocessing, feature engineering, and building a Random Forest classifier to predict customer attrition.

- **credit-card_customers.xlsx**: The raw dataset containing customer information (demographics, financial data, and behaviors).

- **cleaned_credit_card_customers.xlsx**: The cleaned version of the dataset after handling missing values, encoding, and removing irrelevant columns, the cleaning was made using power query.

## Project Workflow

### 1. Data Cleaning and Preprocessing
The dataset was cleaned using power query to handle:
- Missing values
- Incorrect data types
- Encoding of categorical variables (OneHotEncoding and Label Encoding)
  
### 2. Customer Attrition Report
A detailed Power BI report was created to visualize key insights from the dataset. The report highlights:
- Customer segments with the highest churn rates.
- Financial behaviors linked to attrition (e.g., low credit limits, high utilization ratios).
- Demographic trends, including income categories and education levels.

### 3. Machine Learning Model
A machine learning model was developed using a **RandomForestClassifier** from scikit-learn. The model predicts whether a customer will churn based on several features:
- **Demographic Data**: Age, Gender, Dependent count.
- **Behavioral Data**: Total transactions, Credit card utilization, Contact frequency.
- **Financial Data**: Credit limits, Average open balance, etc.

The steps included:
- **Data Preprocessing**: Label encoding for categorical variables and OneHotEncoding for others.
- **Model Training**: Random forest model trained on 70% of the dataset.
- **Model Evaluation**: Accuracy, Precision, Recall, and F1-score were used to evaluate the model’s performance.

## Results
- The model achieved an accuracy of **95%** on the test set, providing significant insights into which factors drive customer churn.
- The Power BI report highlighted that **income level**, **education**, and **credit utilization** are major factors in predicting customer attrition.

## Tools used

- **Python**
- **scikit-learn**
- **pandas**
- **numpy**
- **Power BI Desktop**
- **Excel**


