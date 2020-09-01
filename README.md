# mod3final
README

Project: Readmission Rates for diabetic patients

1. Introduction: 

    Diabetes is a chronic disease in which the body’s ability to produce or respond to the hormone insulin is impaired that causes elevated levels of glucose in the blood and urine. According to the CDC, 34.2 million Americans (10% of Americans) have diabetes.

    High readmission rates cause a high burden to healthcare systems and patients. Diabetes remains one of the greatest risk factors for readmission.

    Project Goal: The goal of this project is to use machine learning to predict the readmission rate for diabetes patients.

2. Data Information: 
    Diabetes dataset comes from UCI Machine Learning Repository. The data contains medical records of 130-US hospitals for years 1999-2008 about the impact of HbA1c Measurement on Hospital Readmission Rates. 
    
3. Data Cleaning and Preping for Model Building
Converted ?s to NaNs
Removed unapplied data
Separated Readmission into >30 days admission, <30 days admission and No admission
Reorganized Medical Specialty

4. Modeling
    a. Linear Regression
    b. Logistic Regression
    c. Random Forest
    d. Gradient Boosting
    e. Extreem Gradient Boosting (XGBoost)

5. Conclusion
    Prediction of hospital readmission for diabetes patients is possible using hospital record data about the diagnostics, medication, lab test results, medical specialty information and procedures given to patients. The models demonstrated that predictions can be made for readmission for diabetes patients. All models (Logistic Regression, XGBoost, and Random Foress) gave an accuracy score of ~ 61%. The models The accuracy is slightly better than a coin toss.
    
6. References



