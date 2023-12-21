# credit-risk-classification
Challenge 20
Purpose: This analysis aims to evaluate credit risk for a lending company by developing a logistic regression machine learning model. The primary goal is to predict the probability of loans being healthy or high-risk, enabling the company to make informed decisions, minimize potential losses, and maintain a robust loan portfolio.
Financial Data Overview: The dataset utilized in this analysis encompasses financial information related to loans. The key variable of interest is "loan_status," indicating whether a loan is healthy (0) or high-risk (1). Various financial attributes such as loan amount, interest rate, annual income, debt-to-income ratio, among others, form the features used to predict the loan status.
Variable Information:
•	Target Variable: "loan_status" denotes the classification of loans into healthy or high-risk.
•	Features: Diverse financial and personal attributes of borrowers utilized for predicting loan status.
Machine Learning Process Stages:
1.	Data Preprocessing:
•	Reading data from a CSV file and creating a Pandas DataFrame.
•	Creating labels (y) from the "loan_status" column and features (X) from other columns.
•	Splitting data into training and testing datasets for model training and evaluation.
2.	Model Development:
•	Employing a Logistic Regression model for predicting loan status.
•	Fitting the model using training data (X_train and y_train).
•	Generating predictions on testing data (X_test) to assess model performance.
3.	Model Evaluation:
•	Constructing a confusion matrix to gauge the model's ability to classify healthy and high-risk loans accurately.
•	Formulating a classification report providing metrics such as accuracy, precision, recall, and F1-score for a comprehensive performance assessment.
4.	Credit Risk Analysis Report:
•	Offering an overview of the analysis and its purpose.
•	Describing accuracy, precision, and recall scores of the machine learning model.
•	Summarizing results and justifying whether the model is recommended for use by the company.
Methods Employed: The principal method utilized is Logistic Regression, a classification algorithm determining odds ratios based on individual characteristics. It predicts loan status (healthy or high-risk) based on borrowers' financial and personal attributes.
Results Overview: Balanced Accuracy Scores:
•	Healthy Loan: 0.99
•	High-Risk Loan: 0.91
•	Balanced Accuracy: 0.95
Precision and Recall Scores:
•	Healthy Loan:
•	Precision = 1.00 (100% accuracy in positive predictions)
•	Recall = 0.99 (99% identification of actual healthy loans)
•	High-Risk Loan:
•	Precision = 0.85 (85% accuracy in positive predictions)
•	Recall = 0.91 (91% identification of actual high-risk loans)
F1-Score:
•	"Healthy Loan": 1.00 (high accuracy and recall)
•	"High-Risk Loan": 0.88 (trade-off between precision and recall)
Summary: Collectively, these metrics indicate that the machine learning model performs well, particularly in identifying healthy loans with high precision and recall. Moreover, it exhibits a balanced performance for high-risk loans, as evidenced by a balanced accuracy of 0.95, demonstrating effectiveness in addressing class imbalances and providing an overall accurate assessment of its performance.

