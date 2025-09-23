# AI-Based Heart Disease Detection using Machine Learning
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/dbe96a1b-5962-4fc2-9553-a732ba5e1041" />


## Project Description
This repository contains the implementation of a predictive model for heart disease detection, as presented in the associated research paper. The project leverages machine learning algorithms in Python to analyze medical data and predict the likelihood of cardiovascular disease in patients. The primary goal is to demonstrate the application of AI in healthcare for early and accurate diagnosis.

## Key features:
- Algorithm: The core model is built using a Random Forest Classifier, chosen for its high accuracy and robustness.
- Data Processing: Handles categorical variables and performs comprehensive data preprocessing, including scaling and correlation analysis.
- Model Evaluation: Achieves an approximate accuracy of 83% on training data, with evaluations conducted using a confusion matrix and other standard metrics.
- Comparative Analysis: Includes implementations and comparisons with other classifiers such as K-Neighbors, Decision Tree, and Support Vector Machines (SVM).
- Technology Stack: Built with standard Python data science libraries including pandas, NumPy, scikit-learn, Matplotlib, and Seaborn.

## Workflow
1. Data loading and exploration.
2. Data preprocessing, including handling outliers, missing values, and duplicates.
3. Exploratory data analysis (EDA) to gain insights into the dataset.
4. Feature selection based on correlation.
5. Train-test split of the dataset.
6. Hyperparameter tuning for multiple machine learning models:
    - Logistic Regression
    - Randomforest
    - Neural Network
7. Model training and evaluation.
8. Display of confusion matrices and classification reports for model performance.

## Results
The Random Forest algorithm provided the best performance among the tested models for this specific dataset, making it a suitable choice for building a reliable heart disease detection system.

## Data content:
The following factors or parameters are considered from the CSV file:
                               
 1   "age"  -  Age of the patient.                              
 2   "sex"  -  Gender of the patient.                         
 3   "chest" -  Chest pain type. (Points from 1 to 4)                            
 4   resting_blood_pressure  -  Resting blood pressure in mm Hg.           
 5   serum_cholestoral  -  Serum cholesterol level in mg/dL.           
 6   fasting_blood_sugar  -   Fasting blood sugar level > 120 mg/dl              
 7   resting_electrocardiographic_results  -   Resting electrocardiographic results (values 0,1,2).
 
 8   maximum_heart_rate_achieved  -  Maximum heart rate achieved      
 9   exercise_induced_angina  -   Exercise-induced angina.            
 10  oldpeak  -  ST depression induced by exercise relative to rest                
 11  slope -  The slope of the peak exercise ST segment                      
 12  number_of_major_vessels  -  Number of major vessels (0-3) colored by flourosopy      
 13  thal  -  3 = normal; 6 = fixed defect; 7 = reversable defect                      
 14  class  -  Absence (1) or presence (2) of heart disease             


### Reference
https://www.kaggle.com/competitions/tech-weekend-data-science-hackathon/data
Chang, V., Bhavani, V. R., Xu, A. Q., & Hossain, M. A. (2022). An artificial intelligence model for heart disease detection using machine learning algorithms. Healthcare Analytics, 2, 100016. 


