#  SaaS Churn Prediction Model with XGBoost

This project builds and evaluates a machine learning pipeline using XGBoost to predict customer churn in a SaaS environment. The model leverages user demographic, behavioral, and engagement features to identify at-risk users and provide actionable insights for business intervention.

---

##  Project Overview

- **Goal**: Predict which users are likely to churn.
- **Model**: XGBoost Classifier
- **Techniques**: Label Encoding, Feature Scaling, SMOTE (for class imbalance), Threshold Tuning, ROC/F1/Confusion Matrix evaluation.

---

## Dataset

-Generated a synthetic 3 synthetic dataset which i merged to get a final dataset named **merged_saas_data.csv**

---

##  Features Used

```text
age, gender, location, preferred_language, device_type,
total_revenue, auto_renew, plan_changes, months_using,
total_watch_time, completion_rate, peak_hour_streaming,
avg_genre_diversity, max_genre, tenure_months, engagement_score,
is_stable_plan, subscription_month, subscription_year,
monthly_avg_revenue

--
