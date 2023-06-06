STROKE PREDICTION PROJECT is to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status
# Dataset Information
gender: "Male", "Female" or "Other"
age: age of the patient
hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
ever_married: "No" or "Yes"
work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
Residence_type: "Rural" or "Urban"
avg_glucose_level: average glucose level in blood
bmi: body mass index
smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
stroke: 1 if the patient had a stroke or 0 if not
Note: "Unknown" in smoking_status means that the information is unavailable for this patient
# Machine Learning model used:
Decision Tree
Random Forest
Logistic Regression
Support Vector Machine
# How to run the app for predict the new data
python app.py
=> The application will run on http://127.0.0.1:5000




