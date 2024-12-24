# Bank Customer Churn Prediction

## Dataset Overview

This dataset is designed for predicting customer churn in a banking environment. Churn is defined as customers who leave the bank—either by closing their accounts or ceasing to use the bank's services.

### Dataset Summary

- **Total Rows**: 10,000
- **Total Columns**: 14
- **Target Variable**: `Exited`
- **Data Type**: Numerical and Categorical

## Objective

The primary goal is to build a predictive model to classify customers as churned or not churned. This can help banks take proactive measures to retain customers and improve satisfaction.

## Results

- **Logistic Regression Accuracy**: 78.3%
- **Decision Tree Accuracy**: 79.35%
- **XGBoost Accuracy**: 85.05%

## Usage

### Example Use Cases:

1. **Predictive Analytics**:
   - Predict which customers are likely to churn.

2. **Customer Segmentation**:
   - Identify characteristics common to customers who churn.

3. **Retention Strategies**:
   - Develop targeted retention campaigns based on customer risk.

## How to Use

1. **Load the Dataset**:
   - Download the dataset from the Kaggle link: [Bank Customer Churn Prediction Dataset](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction)
   - Use Python libraries like pandas to load the dataset for analysis.

2. **Data Preprocessing**:
   - Handle missing or inconsistent values.
   - Encode categorical variables (e.g., `Gender`, `Geography`).

3. **Exploratory Data Analysis (EDA)**:
   - Understand feature distributions.
   - Analyze correlations between features and the target variable.

4. **Model Training**:
   - Split the dataset into training and testing sets.
   - Train machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting).

5. **Model Evaluation**:
   - Evaluate performance using metrics like Accuracy, Precision, Recall, and F1 Score.

## Dependencies

- Python 3.7+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Acknowledgments

The dataset is provided by [Shantanu Dhakad](https://www.kaggle.com/shantanudhakadd) on Kaggle. It is intended for educational purposes and machine learning practice.

## License

Refer to the Kaggle dataset page for licensing details.

