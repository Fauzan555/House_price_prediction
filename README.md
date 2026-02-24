# House Price Sale Prediction Using Logistic Regression
# 📌 Project Overview

This project focuses on predicting whether a house will be sold (Sold = 1) or not (Sold = 0) using Logistic Regression. The dataset contains various housing related attributes such as price, crime rate, air quality, number of rooms, distance measures, rainfall, parks availability, and more.

The goal is to build and analyze classification models using both:

scikit-learn

statsmodels

and interpret the results statistically.

# 📂 Dataset Information

Dataset Name: House_Price.csv

Features:

price

crime_rate

resid_area

air_qual

room_num

age

dist1, dist2, dist3, dist4

teachers

poor_prop

n_hos_beds

n_hot_rooms

rainfall

parks

Sold (Target Variable)

Target Variable:

Sold

1 → House Sold

0 → House Not Sold

# ⚙️ Technologies Used

Python

Pandas

NumPy

Seaborn

Matplotlib

scikit-learn

statsmodels

# 📌 Key Learnings

Price alone is not a strong predictor of sale.

Multiple predictors slightly improve model performance.

Statistical significance is low for most features.

Feature scaling is required for better convergence.

Threshold tuning impacts classification behavior.

Logistic regression assumes linear relationship in log-odds.

# 🚀 Possible Improvements

Apply feature scaling using StandardScaler

Perform feature selection

Remove multicollinearity

Try regularized logistic regression

Evaluate using confusion matrix, ROC curve, AUC

Try advanced classifiers:

Random Forest

Gradient Boosting

XGBoost

# 📌 Conclusion

This project demonstrates the practical implementation of Logistic Regression for binary classification in real estate prediction. While baseline performance is modest, it highlights the importance of:

Proper preprocessing

Statistical interpretation

Model diagnostics

Threshold optimization

It provides a strong foundation for improving predictive modeling in housing datasets.
