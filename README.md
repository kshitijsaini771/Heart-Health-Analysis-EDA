# Heart Disease Risk Analysis (EDA)

## Problem Statement
**Heart disease remains the leading cause of death globally**, yet early identification of at-risk patients can dramatically improve outcomes. This project performs **comprehensive EDA** on 1,025 patient records with 14 clinical features to uncover **key risk factors** and builds **predictive ML models** to support early diagnosis, risk stratification, and clinical decision-making.

---

## Dataset Overview
- **Size:** 1,025 patient records with **14 clinical attributes** (all numeric, no missing values).
- **Target:** Binary classification for **heart disease presence**:
  - **1 (Disease):** 526 patients (**51.3%**).
  - **0 (Healthy):** 499 patients (**48.7%**).
- **Key clinical features:**
  - **Demographics:** `age` (29-77 years, avg **54**), `sex` (69.6% male).
  - **Vitals:** `trestbps` (resting BP: 94-200 mmHg), `chol` (cholesterol: 126-564 mg/dl), `thalach` (max HR: 71-202 bpm).
  - **Risk factors:** `fbs` (fasting blood sugar), `exang` (exercise angina), `oldpeak` (ST depression), `ca` (major vessels), `thal` (thalassemia).
  - **Clinical:** `cp` (chest pain type), `restecg` (ECG results), `slope`.
- **Data quality:** Complete, balanced, and ready for immediate modeling.

---

## EDA & Insights
- **Demographic patterns:**
  - **Age distribution** and gender breakdown reveal typical patient profile (older males predominant).
  - Higher disease prevalence among **middle-aged males**.
- **Cardiovascular analysis:**
  - **Resting BP, cholesterol, max HR** distributions show clear separation between diseased and healthy patients.
  - **Exercise-induced angina** strongly correlates with disease presence.
- **Clinical insights:**
  - **Chest pain types** and **resting ECG** patterns distinguish risk groups.
  - **ST depression (oldpeak)** and **major vessels (ca)** show significant differences.
  - **Thalassemia types** and **fasting blood sugar** flag additional risk.
- **Correlation & risk assessment:**
  - **Strongest predictors:** `oldpeak`, `thal`, `ca`, `cp`, `thalach`.
  - **Age-cholesterol-max HR** interactions highlight combined risk effects.
  - **Gender differences** in BP and other metrics reveal sex-specific patterns.
- **Target comparisons:**
  - **Pairwise clinical measurements** (diseased vs. healthy) identify distinguishing thresholds.
  - **Feature importance** from correlation analysis validates clinical intuition.

---

## How to Use the Notebook
- **Libraries:** pandas, numpy, seaborn, matplotlib, scikit-learn, plotly.
- Open `heart-disease-analysis.ipynb` in **Jupyter**, **JupyterLab**, or **Google Colab**.
- **Run sequentially:**
  1. Data loading and initial exploration.
  2. **EDA visualizations** (histograms, boxplots, heatmaps, pairwise comparisons).
  3. Feature engineering and preprocessing.
  4. **ML model training** with cross-validation and performance metrics.
- **Original notebook:** [Heart Health Analysis (Kaggle)](https://www.kaggle.com/code/kshitijsaini121/heart-health-analysis)
- **Customization:**
  - Test additional algorithms (**Random Forest, XGBoost, SVM**) or **ensemble methods**.
  - Add engineered features (**BMI, age groups**) or **interactions**.
  - Use **GridSearchCV/RandomizedSearchCV** for hyperparameter tuning.
  - Implement **SHAP/LIME** for model interpretability in clinical settings.
  - **Deploy** models with `joblib`/`pickle` for integration into EHR systems or diagnostic apps.

---

## Author & Contact
**Name:** `Kshitij Saini`  
**LinkedIn:** [Kshitij Saini](https://www.linkedin.com/in/kshitijsaini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)
