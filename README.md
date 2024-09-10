**Credit Risk Analysis**
This project involves analyzing a credit risk dataset to explore patterns and insights related to loan approval decisions.

**Dataset**

**Name**: Credit Risk Dataset
**Source**: https://github.com/Premalatha-success/Financial-Analytics-Loan-Approval-Prediction/raw/main/loan_prediction.csv
**Description**: This dataset contains information about applicants' financial history and is used to predict loan approval outcomes.

**Overview**
The Credit Risk dataset includes several financial and demographic factors influencing loan approvals. Through Exploratory Data Analysis (EDA), we examined the distribution and relationships of key variables such as credit score, loan amount, and income. Higher credit scores and lower debt-to-income ratios were found to significantly increase loan approval likelihood, while missed payments and high loan amounts were strong predictors of loan rejections. We applied machine learning models including Logistic Regression, Decision Trees, and Random Forest to predict loan approvals. Logistic Regression emerged as the most reliable, achieving strong performance metrics with a balanced approach to minimizing false positives and negatives, making it suitable for reducing financial risk in credit decisions.

**Inferences**
The high number of true positives indicates that the model is effective at identifying approved loans .There were 15 instances where the model correctly predicted that the loan would not be approved. This indicates that the model is reasonably good at identifying loans that should be rejected. There were 18 cases where the model incorrectly predicted that the loan would be approved when it should not have been. False positives can lead to financial losses if these loans default. There were two cases where the model incorrectly predicted that the loan would not be approved when it should have been. 

•	The Logistic Regression model achieved high accuracy and reliability, making it a strong tool for loan approval decisions .The evaluation metrics highlight the model's strength in capturing eligible applicants. Overall, the logistic regression model provides a strong baseline for predicting loan approvals, minimizing financial risk while maximizing approval rates for creditworthy applicants.

•	Significance of the project : By accurately predicting defaults, the finance company reduces potential losses, safeguarding financial stability.Data-driven insights enhance loan approval processes, fostering informed business decisions.Timely and accurate loan approvals improve customer experience, driving loyalty and retention.
