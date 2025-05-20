# Diabetes-and-Heart-Disease-Prediction
A Python-based project that predict the disease using machine learning. Includes Jupyter Notebook for data analysis, model training, evaluation and visualization. 
This project is a machine learning-based health prediction system that detects the risk of diabetes and heart disease using input from user medical data. It uses trained classification models to help predict the disease in both datasets.

#Features
Heart Dataset:
1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
14. heart disease: 0 = no heart disease, 1 = heart disease.

Diabetes Dataset:
1. Pregnancies: Number of pregnancies.
2. Glucose: Plasma glucose concentration (mg/dL)
3. BloodPressure: Diastolic blood pressure (mm Hg).
4. SkinThickness: Triceps skinfold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml).
6. BMI: Body Mass Index = weight (kg) / height² (m²)
7. DiabetesPedigreeFunction: Higher values = higher genetic risk.
8. Age
9. Outcome: 1 = Diabetic, 0 = Not Diabetic.
   
Description of Diabetes dataset:
-> 768 rows, 9 columns
-> dtypes: float64(2), int64(7).
-> There is no null values in the diabetes dataset 
-> There is no duplicate values in the diabetes dataset 
-> Random Forest Diabetes Cross-Validation Score: 0.7687 
-> SVC diabetes Cross-Validation Score: 0.7622 
-> Random Forest Diabetes Accuracy: 0.7662
-> SVC diabetes Accuracy: 0.7597

Description of Heart dataset:
-> 270 rows, 14 columns
-> dtypes: float64(1), int64(13)
-> There is no null values in the diabetes dataset 
-> There is no duplicate values in the diabetes dataset
-> Random Forest Diabetes Cross-Validation Score: 0.8198
-> SVC diabetes Cross-Validation Score: 0.7920 
-> Random Forest Diabetes Accuracy: 0.8519
-> SVC diabetes Accuracy: 0.8889

-> Predict the person is diabetic or not, heart disease or not with new data.
-> Predict the risk percentage in patient.
