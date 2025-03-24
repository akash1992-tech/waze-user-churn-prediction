# 🚗 Waze User Churn Prediction

## 📈 Project Overview
This project aims to predict user churn in the Waze app using machine learning. The focus is on inspecting, organizing, and preparing user activity data to build a churn prediction model.

---

## 🗂 Dataset Summary
**Filename**: `waze_dataset.csv`  
**Rows**: 14,999 (unique users)  
**Columns**: 13  

| Column Name               | Data Type | Description                                                                                  |
|---------------------------|----------|----------------------------------------------------------------------------------------------|
| ID                        | int      | Unique user index                                                                            |
| label                     | object   | Target variable: `retained` or `churned`                                                     |
| sessions                  | int      | Number of times the app was opened during the month                                          |
| drives                    | int      | Number of driving sessions (≥1 km)                                                           |
| device                    | object   | Device type used to start a session                                                          |
| total_sessions            | float    | Estimated total sessions since onboarding                                                    |
| n_days_after_onboarding   | int      | Days since the user signed up                                                                |
| total_navigations_fav1    | int      | Total navigations to favorite place 1                                                        |
| total_navigations_fav2    | int      | Total navigations to favorite place 2                                                        |
| driven_km_drives          | float    | Total kilometers driven during the month                                                     |
| duration_minutes_drives   | float    | Total driving duration in minutes during the month                                           |
| activity_days             | int      | Number of days the user opened the app during the month                                      |
| driving_days              | int      | Number of days the user drove during the month                                               |

---

## ✅ Project Tasks Completed
- Data import and review
- Data type and missing value inspection
- Descriptive statistics generation
- Initial observations for further analysis

---

## 🛠 Tools & Technologies
- Python
- pandas
- numpy
- Jupyter Notebook
