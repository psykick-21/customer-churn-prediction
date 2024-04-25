# Customer Churn Prediction (Classification)

Data source: Kaggle [Customer Churn Dataset](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset)<br>
License: [GPL-2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)


## About the project
Customer churn refers to the phenomenon where customers discontinue their relationship or subscription with a company or service provider. It represents the rate at which customers stop using a company's products or services within a specific period. Churn is an important metric for businesses as it directly impacts revenue, growth, and customer retention.

In the context of the Churn dataset, the churn label indicates whether a customer has churned or not. A churned customer is one who has decided to discontinue their subscription or usage of the company's services. On the other hand, a non-churned customer is one who continues to remain engaged and retains their relationship with the company.

Understanding customer churn is crucial for businesses to identify patterns, factors, and indicators that contribute to customer attrition. By analyzing churn behavior and its associated features, companies can develop strategies to retain existing customers, improve customer satisfaction, and reduce customer turnover. Predictive modeling techniques can also be applied to forecast and proactively address potential churn, enabling companies to take proactive measures to retain at-risk customers.

## Modeling
Various ML Algorithms were used like Logistic Regression, KNN, SVM, Decision Tree, Random Forest, XGBoost, LightGBM, AdaBoost, CatBoost and Stacking Ensemble. The best performing model (logloss as the metric) was Stacking Ensemble with XGBoost as the final estimator. Best metrics: 93.6% accuracy, 0.897 precision and 0.181 logloss. For more metrics, please refer to the notebook.
