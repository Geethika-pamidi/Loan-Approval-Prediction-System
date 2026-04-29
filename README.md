Neural Network-Enhanced Loan Approval & Credit Risk System

A complete comparison of 5 classical machine learning models against a PyTorch Neural Network for automated loan approval prediction.
Problem Statement:
"Manual loan underwriting is slow and prone to human error. This project automates the credit risk assessment process by analyzing 50,000+ data points to provide instant, high-precision loan approval decisions, reducing financial risk for lenders and improving the user experience for applicants."
Dataset--
- 50,000 loan records
- 20 features: credit score, annual income, debt-to-income ratio, 
  loan amount, employment status, etc.
- Target: loan_status (1 = Approved, 0 = Rejected)
"I developed the end-to-end pipeline: from data cleaning and feature engineering (handling 20+ variables) to benchmarking 5 classical ML models (SVM, KNN, etc.). I then designed and trained a custom PyTorch Neural Network to optimize predictive accuracy beyond traditional methods."

Model | Accuracy |
Naive Bayes | ~80% |
Decision Tree | ~84% |
Logistic Regression | ~85% |
KNN | ~86% |
SVM | 88.7% |
Neural Network (PyTorch) | 90%|

Tools & Technologies
- *Language:* Python
- *Deep Learning:* PyTorch
- *Classical ML:* Scikit-Learn
- *Data Processing:* Pandas, NumPy
- *Visualization:* Matplotlib, Seaborn
- *Environment:* Jupyter Notebook

Conclusions
1. Neural Networks outperform classical ML on large financial datasets
2. SVM is strongest classical baseline — fast and accurate
3. Dropout successfully prevented overfitting
4. Automated loan approval reduces bias and scales to millions of applications
