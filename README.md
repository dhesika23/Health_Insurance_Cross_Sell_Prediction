# Health_Insurance_Cross_Sell_Prediction

# Project Overview

This project focuses on developing machine learning models to predict customer responses to insurance products using demographic and historical data. The goal is to help an insurance company identify potential customers who are likely to be interested in purchasing vehicle insurance based on their existing health insurance policies.

# Exploratory Data Analysis (EDA)

The EDA phase involved:

Understanding the distribution of features
Identifying and handling missing values
Detecting and treating outliers
Assessing correlations with the target variable
Visualization techniques such as histograms, bar plots, box plots, and heatmaps were utilized to extract insights.

# Data Preprocessing

# Key preprocessing steps included:

Handling missing values
Encoding categorical variables
Scaling numerical features
Splitting the data into training and testing sets
Addressing class imbalance through SMOTE (Synthetic Minority Over-sampling Technique) to ensure balanced training data
Model Development

# Three machine learning models were implemented:

Logistic Regression
Random Forest Classifier
Gradient Boosting Classifier
Hyperparameter tuning was conducted using GridSearchCV and RandomizedSearchCV to optimize model performance.
Cross-validation was employed to ensure robustness.
Model Evaluation
Models were evaluated using the following metrics:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix for deeper insights into performance
The Gradient Boosting Classifier emerged as the top-performing model with an accuracy of 87.53% on the test set. However, the model showed lower precision, recall, and F1-score for the positive class, indicating challenges in accurately classifying customers likely to respond positively.

Model Interpretability

SHAP (SHapley Additive exPlanations) values were used to interpret the model, highlighting feature importance:

Vehicle Age and Vintage were significant factors, with older vehicles and longer customer relationships being positively associated with a higher likelihood of positive responses.

# Conclusion

The machine learning models developed in this project offer valuable predictive insights for the insurance company. The Gradient Boosting Classifier, despite its strong overall accuracy, could benefit from further refinement to improve the classification of positive instances. SHAP analysis provides strategic insights for targeting insurance products, particularly towards customers with older vehicles and longer relationships with the company.
