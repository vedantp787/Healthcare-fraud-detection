# Healthcare Fraud Detection – Case Study 

This project focuses on detecting fraudulent healthcare providers using machine learning techniques. The analysis is based on simulated datasets representing beneficiary details, inpatient/outpatient claims, and provider fraud labels. This case study aligns with a real-world internship challenge provided by Sagility (formerly part of Hinduja Global Solutions).

## 🔍 Problem Statement

Healthcare fraud detection is crucial in minimizing losses to the healthcare system. Using historical claim data, our goal is to predict whether a given provider is likely to be fraudulent based on patterns in inpatient, outpatient, and beneficiary records.

## 🗂 Dataset

The dataset contains four CSV files:

- `Inpatient.csv` – Contains inpatient claim records.
- `Outpatient.csv` – Contains outpatient claim records.
- `Beneficiary.csv` – Contains beneficiary information like age, chronic conditions, etc.
- `Train-Labels.csv` – Binary labels indicating whether a provider is fraudulent.

> **Note:** This project uses simulated data from [this Kaggle dataset](https://www.kaggle.com/datasets/rohitrox/healthcare-provider-fraud-detection-analysis).

## ⚙️ Approach

1. **Data Preprocessing**
   - Merging inpatient/outpatient records with beneficiary data
   - Handling missing values
   - Feature engineering (e.g., number of chronic conditions, total claims, etc.)

2. **Exploratory Data Analysis (EDA)**
   - Understanding fraud vs. non-fraud patterns
   - Visualizations of claim amounts, procedures, and diagnoses

3. **Model Building**
   - Tested multiple models: Logistic Regression, Random Forest, XGBoost
   - Balanced the dataset using SMOTE or undersampling
   - Evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC

4. **Insights & Recommendations**
   - Key features influencing fraud prediction
   - Suggested how model could be deployed in real-time fraud flagging systems

## 📁 Files

- `fraud_detection.html` – Full Jupyter Notebook (exported as HTML) with code, visualizations, and results.\
- 'Project_PPT' - Shows the details of the project through Visualizations

## ✅ Results

- Achieved up to **75% accuracy** after preprocessing and balancing.
- Feature importance revealed patterns in claim duration, chronic diseases, and abnormal billing behaviors.


## 📚 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Machine Learning (Random Forest, XGBoost)
- SMOTE for class imbalance
- Git & GitHub for version control

## 🙋‍♂️ Author

**Vedant Patil**  
📍 Pune, India  
📧 vp717773@gmail.com  
🔗 [LinkedIn]-https://www.linkedin.com/in/vedantpatil31/

---

