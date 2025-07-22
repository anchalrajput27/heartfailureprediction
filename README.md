# 💓 Predictive Modeling on Heart Failure Clinical Records Dataset

This project uses **Logistic Regression** to predict the likelihood of death events in patients based on clinical features from the [Heart Failure Clinical Records Dataset](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data). The model achieves **over 80% accuracy** on both training and testing data, indicating good generalization and reliability.

## 📊 Dataset Overview

- **Source**: Kaggle - Heart Failure Clinical Records Dataset
- **Instances**: 299
- **Features**: 13 clinical features + 1 target (`DEATH_EVENT`)
- **Target Variable**:  
  - `DEATH_EVENT`: 1 if the patient died during the follow-up period, 0 otherwise

## 🔍 Features Used

| Feature Name       | Description                                  |
|--------------------|----------------------------------------------|
| age                | Age of the patient                           |
| anaemia            | Decrease of red blood cells or hemoglobin    |
| creatinine_phosphokinase | Level of the CPK enzyme                  |
| diabetes           | If the patient has diabetes                  |
| ejection_fraction  | Percentage of blood leaving the heart each time it contracts |
| high_blood_pressure| If the patient has hypertension              |
| platelets          | Platelet count in the blood                  |
| serum_creatinine   | Level of creatinine in the blood             |
| serum_sodium       | Level of sodium in the blood                 |
| sex                | Gender of the patient                        |
| smoking            | If the patient smokes                        |
| time               | Follow-up period (in days)                   |
| DEATH_EVENT        | Target (1 = died, 0 = survived)              |

## 🧠 Model Used

- **Logistic Regression** (Binary classification)

### ✅ Evaluation Metrics

- **Accuracy**: > 80% on both training and test sets
