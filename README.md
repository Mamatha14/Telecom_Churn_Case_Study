# Telecom_Churn_Case_Study
### Problem Statement:
- Predicting customers who are at high risk of churning (Customer Retention), thereby reducing the churn rate.
- Building predictive models to identify customers at high risk of churn and identify the main indicators for churn.
### Steps Involved:
- Data Understanding
- Data Cleaning
- Data Preparation: Derive New Features, Filter high value customers, Tag Churners.
- Model Building:
  - 2 Models:
    1. Interpretable Model without PCA: Logistic Regression
    2. High Performance Model with PCA: Logistic Regression, Random Forest and XGBoost
### Conclusion:
- For customer churn, the metric choosen to find the best model is the Sensitivity Metric and hence, out of all four models, the best model for predicting the customer churn is Random Forest with PCA with following statistics:
  - Train Set:
    - Accuracy: 87.55%
    - Sensitivity: 76.85%
  - Test Set:
    - Accuracy: 87.44%
    - Sensitivity: 75.45%
- Top 5 important Predictors and their absolute co-efficient values:
  1. loc_ic_t2m_mou_8: 0.7961
  2. sep_vbc_3g: 0.4656
  3. total_rech_amt_8: 0.3759
  4. loc_ic_t2t_mou_8: 0.3481
  5. total_rech_amt_g: 0.2364
  6. loc_ic_t2m_mou_g: 0.1801
- Strategies to manage customer churn: From the top predictors it looks like amount of recharge is an important parameter and hence the telecom operator can provide better and attractive recharge packages and offers to retain the churn customers.
