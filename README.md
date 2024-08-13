# Machine-Learning-Repository
Project 4

MACHINE LEARNING VS CREDIT SCORE

This project focuses on creating a machine learning model to evaluate the relative importance of various expenditure features and their relevance in determining an individual's credit score based off of their expenditure's importance. The features considered are:

Clothing
Education
Entertainment
Fines
Gambling
Groceries
Health
Housing
Tax
Travel
Utilities

The goal is to understand which of these factors has the most significant impact on expenditures, which plays a major role when it comes to expenditure and debt which is relevant to credit score.

Project Structure
The project is organized into the following sections:

Data Collection and Preprocessing
Model Development
Feature Importance Analysis
Results and Interpretation
Conclusion

Data Collection and Preprocessing
Data Source: https://www.kaggle.com/datasets/conorsully1/credit-score

Data Features: The dataset includes the following features:
Credit Score: The dependent variable.
Income: Annual income.
Debt: Total outstanding debt.
Savings: Amount of savings available.
Expenditure: Annual expenditure.

Preprocessing Steps:
Handle missing data
Normalize/scale the features
Split the data into training and testing sets

Model Development
The model used is the Random Forest Regressor Model

Training: The models will be trained using the training dataset, and hyperparameter tuning will be performed to optimize model performance.
Evaluation: Models will be evaluated based on metrics such as Mean Squared Error (MSE), R-squared, and others.

Feature Importance Analysis
Techniques Used: The feature importance will be assessed using:
Coefficients from linear models
Feature importance scores from tree-based models (e.g., Gini Importance or Mean Decrease in Impurity)
Visualization: Feature importance will be visualized using bar charts, feature importance plots, and SHAP summary plots.

Results and Interpretation
Feature Ranking: The features will be ranked based on their importance scores.
Analysis: Detailed analysis on how each feature contributes to predicting the credit score will be provided.
Insights: Insights will be drawn regarding which financial behaviors (e.g., reducing debt or increasing savings) are most crucial for improving credit scores.

Summary: A summary of the findings and the effectiveness of the model.
Recommendations: Practical recommendations for individuals or institutions based on the feature importance analysis.
Future Work: Suggestions for further research or model improvements, such as incorporating additional features like employment history, loan types, or credit history duration.

