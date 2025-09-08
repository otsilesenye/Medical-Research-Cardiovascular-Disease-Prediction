# Medical-Research-Cardiovascular-Disease-Prediction
Worked with complex health datasets to build predictive models assessing the likelihood of cardiovascular disease.

Cardiovascular Disease Prediction

Overview
This project investigates how lifestyle factors influence the likelihood of developing cardiovascular disease (CVD). Using a medical dataset, we applied machine learning models to identify key predictors and assess how behaviors like smoking, drinking, and physical activity interact with health metrics such as cholesterol and glucose levels.

Data:
Source: Kaggle - Cardiovascular Disease Dataset (https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)

Size: ~65,000 rows, 13 features

Notes: Anonymized health data including age, gender, blood pressure, cholesterol, glucose, and lifestyle indicators

Methodology
Converted age from days to years and validated categorical values

Removed outliers in blood pressure using IQR method

Performed EDA on BMI, cholesterol, glucose, and activity levels

Applied classification models:

K-Nearest Neighbors (KNN)

Logistic Regression

Random Forest

Decision Tree

Visualized feature importance and confusion matrices

Key Insights
High cholesterol and glucose levels significantly increase CVD risk

Physical activity mitigates risk across most lifestyle factors

Decision Tree classifier achieved the highest accuracy (72.66%) among models tested

Tech Stack
Python (pandas, scikit-learn, matplotlib), SQL, Tableau
