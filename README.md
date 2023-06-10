Credit Risk Analysis Report

Overview:
This analysis aims to evaluate two logistic regression models for loan risk classification. The goal is to determine how well they predict healthy loans (Class 0) and high-risk loans (Class 1). We will compare their accuracy, precision, recall, and f1-score to assess their performance.

Results:

Model 1 - Logistic Regression Model with Original Data:

Accuracy Score: 95%
Precision Score (Class 0 - Healthy Loan): 100%
Precision Score (Class 1 - High-Risk Loan): 85%
Recall Score (Class 0 - Healthy Loan): 99%
Recall Score (Class 1 - High-Risk Loan): 91%
f1-Score (Class 0 - Healthy Loan): 100%
f1-Score (Class 1 - High-Risk Loan): 88%
Model 2 - Logistic Regression Model with Resampled Training Data:

Accuracy Score: 99%
Precision Score (Class 0 - Healthy Loan): 100%
Precision Score (Class 1 - High-Risk Loan): 84%
Recall Score (Class 0 - Healthy Loan): 99%
Recall Score (Class 1 - High-Risk Loan): 99%
f1-Score (Class 0 - Healthy Loan): 100%
f1-Score (Class 1 - High-Risk Loan): 91%
Summary:
After evaluating the two models, it is clear that Model 2, trained on a resampled training dataset, outperforms Model 1, which uses the original data.

Model 1 achieved a respectable accuracy score of 95%. It accurately predicted healthy loans (Class 0) with a precision score of 100%, meaning very few non-risky loans were mistakenly classified as high-risk. However, the precision score for high-risk loans (Class 1) was 85%, suggesting a higher number of false alarms. The recall scores were decent, with 99% for healthy loans and 91% for high-risk loans. The f1-scores were 100% for Class 0 and 88% for Class 1.

Model 2, on the other hand, showed significant improvement with an impressive accuracy score of 99%. It maintained perfect precision in identifying healthy loans (Class 0). However, the precision score for high-risk loans (Class 1) decreased slightly to 84%, indicating a slightly higher number of false alarms. The recall score for high-risk loans increased significantly to 99%, meaning the model successfully captured most of the actual high-risk loans. The f1-scores for Class 0 and Class 1 were both high, with 100% and 91%, respectively.

Based on the results, we recommend using Model 2 for loan risk classification. This model achieved higher accuracy, precision, recall, and f1-scores, indicating its effectiveness in accurately identifying both healthy and high-risk loans. By adopting Model 2, the company can make more informed decisions, reduce false alarms, and better manage the risks associated with high-risk loans.
