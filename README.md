# Elevate_Labs-FInal-project
# Predicting No-Shows for Medical Appointments Using Machine Learning

 Introduction
Missed medical appointments lead to scheduling inefficiencies, wasted resources, and reduced quality of healthcare services. This project aims to predict whether a patient will attend their medical appointment using historical data and machine learning techniques.



 Dataset
 **Source**: [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
 **Records**: 110,527 rows
 **Features Include**:
   Patient demographics (Age, Gender)
   Health conditions (Hypertension, Diabetes, Alcoholism, Handicap)
   Appointment details (Scheduled Day, Appointment Day, SMS Received)
   Target variable: `No-show`



 Tools & Libraries Used
 **Python**
 **Jupyter Notebook**
 **Pandas, NumPy**
 **Matplotlib, Seaborn**
 **Scikit-learn**



 Steps Involved
1. **Data Collection & Preprocessing**
    Converted dates to datetime
    Removed irrelevant columns
    Handled anomalies like negative ages
    Encoded target variable

2. **Exploratory Data Analysis (EDA)**
    Analyzed age, gender, and medical condition distributions
    Plotted attendance behavior with SMS and scholarship info

3. **Modeling**
    Logistic Regression
    K-Nearest Neighbors (KNN)
    Random Forest Classifier

4. **Evaluation**
    Accuracy, Precision, Recall
    Confusion Matrix
    Best model: Random Forest (~79% Accuracy)



 Results
 Younger patients and those who didn’t receive SMS reminders were more likely to miss appointments.
 Random Forest outperformed other models with better prediction performance.



 Conclusion
Machine learning can help healthcare providers reduce no-shows by predicting appointment attendance. With better scheduling, reminders, and patient management, such models can lead to improved efficiency and patient care.



## Project Structure
 medical-no-show-prediction
 Predicting_medical_appointments.ipynb
 README.md
 Medical_No_Show_Report.docx
 dataset

## Future Work
  Include time of appointment (morning/evening)
  Add external weather data
  Integrate with hospital alert systems

##  License
This project is for educational purposes and is not licensed for commercial healthcare applications.

## Author
**Sireesha** – MCA Student specializing in AI & ML



