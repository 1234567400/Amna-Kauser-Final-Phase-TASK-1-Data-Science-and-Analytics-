# Amna-Kauser-Final-Phase-TASK-1-Data-Science-and-Analytics-
Data Science and Analytics Internship Tasks
Data Science and Analytics Internship Task

Objective
Build and evaluate classification models to predict whether a client will subscribe to a term deposit using marketing data, and use explainability techniques to understand predictions.

Approach

Data Analysis: Explored 11,162 records with 17 features, checked class balance (no: 52.6%, yes: 47.4%), and visualized relationships.
Feature Engineering: Created features like age_group, balance_group, campaign_intensity, and previous_success.
Model Training: Applied Logistic Regression, Decision Tree, and Random Forest using 5-fold cross-validation with F1-score.
Explainability: Used SHAP on the best model to explain predictions and identify important features.

Results and Insights

Best Model: Random Forest performed best (F1: 0.834, AUC-ROC: 0.910), outperforming others.
Key Features: Call duration was the most important factor, followed by housing loan status, previous success, and campaign contacts.
Insights: Longer calls increase subscription chances, while housing loans and too many contacts reduce it, helping improve marketing strategies.
