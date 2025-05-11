#  Heart Disease Prediction using Machine Learning

This project leverages various machine learning and data science libraries in Python to build a classification model capable of predicting the presence of heart disease based on clinical and diagnostic patient data.

---

##  Problem Definition

**Can we accurately predict whether a patient has heart disease based on their medical attributes?**

Given a set of clinical features describing a patient (such as age, sex, cholesterol levels, etc.), the goal is to create a machine learning model that determines the likelihood of the presence of heart disease.

---

## 📊 Dataset

* **Source**: [UCI Machine Learning Repository – Heart Disease Dataset (Cleveland)](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
* The dataset contains 14 attributes and a target variable indicating the presence (`1`) or absence (`0`) of heart disease.

---

## 𞳒 Data Dictionary

| Feature    | Description                                                                                                                 |
| ---------- | --------------------------------------------------------------------------------------------------------------------------- |
| `age`      | Age in years                                                                                                                |
| `sex`      | Gender (1 = male, 0 = female)                                                                                               |
| `cp`       | Chest pain type:<br> 0 = Typical angina<br> 1 = Atypical angina<br> 2 = Non-anginal pain<br> 3 = Asymptomatic               |
| `trestbps` | Resting blood pressure (mm Hg). Above 130–140 is cause for concern.                                                         |
| `chol`     | Serum cholesterol in mg/dl. Above 200 is cause for concern.                                                                 |
| `fbs`      | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false). Over 126 mg/dl signals diabetes.                                     |
| `restecg`  | Resting ECG results:<br> 0 = Normal<br> 1 = ST-T wave abnormality<br> 2 = Possible or definite left ventricular hypertrophy |
| `thalach`  | Maximum heart rate achieved                                                                                                 |
| `exang`    | Exercise-induced angina (1 = yes; 0 = no)                                                                                   |
| `oldpeak`  | ST depression induced by exercise relative to rest                                                                          |
| `slope`    | Slope of the peak exercise ST segment:<br> 0 = Upsloping<br> 1 = Flat<br> 2 = Downsloping                                   |
| `ca`       | Number of major vessels (0–3) colored by fluoroscopy                                                                        |
| `thal`     | Thalium stress test result:<br> 1, 3 = Normal<br> 6 = Fixed defect<br> 7 = Reversible defect                                |
| `target`   | Target variable:<br> 0 = No heart disease<br> 1 = Presence of heart disease                                                 |

---

##  Approach

1. **Problem Definition**
   Define the classification task: Predicting heart disease from clinical parameters.

2. **Data Exploration**
   Understand data structure, clean missing or inconsistent entries, and perform exploratory data analysis (EDA).

3. **Feature Engineering**
   Convert categorical variables, scale features, and select relevant attributes.

4. **Model Building**
   Train various machine learning classifiers (e.g., Logistic Regression, KNN, Random Forest) and evaluate performance.

5. **Evaluation Metrics**
   Assess model accuracy, precision, recall, F1-score, and confusion matrix.

6. **Experimentation & Optimization**
   Use cross-validation and hyperparameter tuning to improve model performance.

---

##  Technologies Used

* Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* Jupyter Notebook
* Machine Learning Algorithms: Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, etc.

---

##  Outcome

A machine learning model that predicts the presence of heart disease with measurable accuracy, which can assist in early diagnosis and preventive care.

---

##  License

This project is for educational and research purposes only.

---

##  Acknowledgements

* UCI Machine Learning Repository
* Open-source ML & Data Science community
