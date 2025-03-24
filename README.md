:

🚗 Waze User Churn Prediction - Data Inspection & Preparation
📈 Project Overview
This project is part of the Waze User Churn Prediction initiative. The objective of this phase is to inspect, organize, and prepare Waze user activity data for machine learning modeling. The analysis will help the team understand user behaviors that may lead to churn and set the stage for predictive modeling.

The dataset contains synthetic user data representing app usage, driving behaviors, and retention status.

🗂 Dataset Summary
Filename: waze_dataset.csv
Rows: 14,999 unique users
Columns: 13 variables

Column Name	Data Type	Description
ID	int	Unique sequential user index
label	object	Binary target: retained or churned
sessions	int	Number of times the app was opened in a month
drives	int	Number of driving sessions (≥1 km driven)
device	object	Device type used to start a session
total_sessions	float	Estimated total sessions since onboarding
n_days_after_onboarding	int	Number of days since the user signed up
total_navigations_fav1	int	Total navigations to favorite place 1
total_navigations_fav2	int	Total navigations to favorite place 2
driven_km_drives	float	Total kilometers driven during the month
duration_minutes_drives	float	Total driving duration in minutes during the month
activity_days	int	Number of days the app was opened in the month
driving_days	int	Number of days the user drove in the month
✅ Project Tasks Completed
Loaded and reviewed the dataset

Checked data types for each variable

Identified missing values

Generated descriptive statistics

Summarized initial insights and observations for EDA

🛠 Tools & Technologies
Python

pandas

numpy

Jupyter Notebook

