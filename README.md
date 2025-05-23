# employee-retention-risk
# 🧠 Employee Retention Risk Prediction

Predict employee tenure and salary raise (to gauge if they're likely to feel under-compensated).  Then, classify retention risk using linear regression models.  

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Overview

This project builds two linear regression models to predict:
- **YearsAtCompany** (tenure)
- **PercentSalaryHike** (raise %)

Then combines those into a **Retention Risk Score**:
- High Risk: likely to leave soon
- Medium Risk: either tenure or hike is below average
- Low Risk: expected to stay and feels well-compensated

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔧 Tools & Techniques

- Python, pandas, scikit-learn
- Linear regression
- Feature engineering (ratios, interactions)
- Risk classification logic using percentiles
- Model evaluation with RMSE & MAE

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Performance

| Model                 | R²    | Avg Error |
|----------------------|-------|-----------|
| YearsAtCompany       | 0.83  | 1.6 years |
| PercentSalaryHike    | 0.61  | 1.9%      |






