# Heart Disease Analysis

## Overview
Comprehensive analysis of 1,025 patient records to identify key factors contributing to heart disease. Built machine learning models achieving strong predictive accuracy to support early diagnosis and medical decision-making in cardiovascular care.

## Dataset Overview
- **Size**: 1,025 patient records with 14 clinical attributes covering demographics, test results, and disease presence.
- **Target Variable**: Binary classification where 1 indicates presence of heart disease (51.3% of patients) and 0 indicates absence (48.7%).
- **Key Features**: Age (29-77 years, avg 54), sex (69.6% male), chest pain type (cp), resting blood pressure (trestbps), cholesterol (chol), fasting blood sugar (fbs), resting ECG results (restecg), max heart rate (thalach), exercise-induced angina (exang), ST depression (oldpeak), slope, number of major vessels (ca), and thalassemia (thal).
- **Data Quality**: Complete dataset with no missing values, all numeric features ready for modeling.
- **Clinical Ranges**: Blood pressure ranges from 94-200 mmHg, cholesterol from 126-564 mg/dl, and max heart rate from 71-202 bpm.
- **Target Distribution**: Fairly balanced dataset with 526 heart disease patients and 499 healthy individuals.

## Analysis Performed

- **Demographic Analysis**: Examined average age of patients and gender distribution to understand the patient population characteristics
- **Cardiovascular Metrics**: Analyzed resting blood pressure, maximum heart rate achieved, and cholesterol levels to assess cardiovascular health indicators
- **Clinical Parameters**: Investigated fasting blood sugar levels, exercise-induced angina prevalence, and chest pain type distributions
- **Electrocardiographic Results**: Evaluated resting ECG findings including left ventricular hypertrophy patterns across patient groups
- **Fluoroscopy Analysis**: Analyzed distribution of major vessels colored by fluoroscopy (ca) and its relationship with heart disease
- **Correlation Studies**: Examined relationships between age and cholesterol, maximum heart rate and exercise-induced angina, and oldpeak values across chest pain types
- **Gender-based Comparison**: Investigated differences in resting blood pressure and other clinical measurements between male and female patients
- **Risk Factor Assessment**: Analyzed fasting blood sugar levels, thalassemia types, and combinations of multiple risk factors in relation to heart disease presence
- **Target Variable Analysis**: Performed pairwise comparisons of clinical measurements for patients with and without heart disease to identify distinguishing patterns
- **Feature Importance**: Identified clinical measurements with strongest correlations to heart disease presence and analyzed combined effects of age, cholesterol, and blood pressure on disease likelihood
## How to Use

- Common libraries include pandas, numpy, seaborn, matplotlib, and scikit-learn.
- Open `heart-disease-analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
- Run cells sequentially from top to bottom for data loading, cleaning, visualization, and model training.
- Original Kaggle notebook:  
[heart-disease-analysis](https://www.kaggle.com/code/kshitijsaini121/heart-health-analysis)
- Customize the analysis:  
- Experiment with different ML algorithms or ensemble methods to improve prediction accuracy.
- Add new features like BMI or lifestyle factors if available.
- Tune hyperparameters using GridSearchCV or RandomizedSearchCV for optimal model performance.
- Deploy models using joblib or pickle for integration into healthcare systems or diagnostic tools.

## Author & Contact
- Name: `Kshitij Saini`    
- LinkedIn: [https://www.linkedin.com/in/kshitijsaini](https://www.linkedin.com/in/kshitij-saini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)




  
