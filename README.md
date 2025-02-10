# **Credit Risk Modeling & Loan Limit Recommendation**

## **Project Overview**
This project focuses on building a **credit risk model** to predict loan defaults and developing an algorithm to recommend personalized loan limits. The goal is to reduce the default rate and maximize profit for a lending business.

## **Dataset**
- **File:** `loan_default_1_smpl.csv`
- **Records:** 47,728 historical loans
- **Key Column:** `Status` (1 = Default, 0 = Non-default)
- **Average Loan Amount:** $334,000

## **Objectives**
1. Build a **credit risk model** to predict loan default probability.
2. Develop an algorithm to **recommend loan limits** for new borrowers.
3. Propose a strategy for **scaling and productionizing** the model.

## **Production Considerations**
- Handling a **large dataset** with more features (~50,000).
- Scaling to **5,000 loan applications per day**.
- Efficient model deployment and monitoring.

## **Technologies Used**
- Python (Pandas, NumPy, Scikit-learn)
- Machine Learning (Logistic Regression, Random Forest, XGBoost)
- FastAPI (for model deployment)
- Docker & Uvicorn (for scalability)
