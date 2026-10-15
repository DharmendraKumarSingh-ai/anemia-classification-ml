# Anemia Classification Using Blood Parameters

## 📌 Project Overview
This project uses Machine Learning to classify anemia-related categories based on blood parameters such as Hemoglobin (Hb), RBC, PCV, MCV, MCH, and MCHC.

The main objective is to analyze blood test data, train classification models, evaluate their performance, and develop a system that predicts the target class from the provided input parameters.

## 🎯 Objectives
- Analyze and preprocess blood parameter data.
- Perform Exploratory Data Analysis (EDA).
- Train Machine Learning classification models.
- Compare model performance using evaluation metrics.
- Predict the target class using blood parameters.
- Build a user-friendly application for predictions.

## 📊 Dataset Description
The dataset contains 1,000 original records and 9 columns.

**Features:**
- `Gender` — Gender of the individual
- `Age` — Age
- `Hb` — Hemoglobin level
- `RBC` — Red Blood Cell count
- `PCV` — Packed Cell Volume
- `MCV` — Mean Corpuscular Volume
- `MCH` — Mean Corpuscular Hemoglobin
- `MCHC` — Mean Corpuscular Hemoglobin Concentration

**Target Variable:**
- `Decision_Class` — Classification label
  - `0` — Normal / Non-anemic (provisional mapping)
  - `1` — Anemia (provisional mapping)

*Note: The target-label mapping should be verified against the original dataset documentation.*

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
  

## ⚙️ Project Workflow
1. Load and inspect the dataset.
2. Clean duplicate records and handle missing values.
3. Perform Exploratory Data Analysis.
4. Split the dataset into training and testing sets.
5. Preprocess numerical and categorical features.
6. Train classification models.
7. Evaluate and compare model performance.
8. Save the selected trained model.
9. Build a Streamlit application for predictions.

## 🤖 Machine Learning Algorithms
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual evaluation results will be added after training and testing the models.



## 🔮 Future Improvements
- Validate the model using additional independent datasets.
- Improve model generalization and evaluation.
- Add clear visualizations to the web application.
- Deploy the application online.
- Document the dataset source and target-label definitions.

## ⚠️ Disclaimer
This project is developed for educational and research purposes only. It is not a medical diagnostic tool. Predictions should not be used to diagnose or treat any medical condition. Consult a qualified healthcare professional for medical interpretation.

## 👨‍💻 Author
**Your Name**

GitHub: [(https://github.com/DharmendraKumarSingh-ai/)]
