# **Mental Health Analysis using Machine Learning**

## **Objective**
This project aims to analyze mental health survey data to uncover key insights and build predictive models for identifying individuals experiencing mood swings. The goal is to support mental health awareness by leveraging data-driven approaches.

---

## **Dataset**
- Format: CSV
- Key Features: Gender, Occupation, Family History, Self-Employment, Treatment, Growing Stress, Coping Struggles, etc.
- Target Variable: `Mood_Swings`

---

## **Steps and Methodology**

- **Preprocessing**:
  - Cleaned missing values and label-encoded all categorical features.
  - Final dataset: 1000+ cleaned records, 100% free from nulls.

- **Exploratory Analysis**:
  - Students represented **~30%** of the sample and showed higher mental health struggles.
  - Females had a **higher incidence of treatment-seeking behavior**.

### **Model Building**
- Built and evaluated multiple classification models:
  - Decision Tree Classifier
  - Random Forest Classifier
  - XGBoost Classifier
- Used pipelines for cleaner and more modular model training.

- **Results**:
  - Trained Decision Tree, Random Forest, and XGBoost classifiers.
  - **XGBoost** achieved:
    - **AUC Score**: 0.91
---

## **Conclusion**
- The Random Forest and XGBoost classifiers performed best in identifying individuals experiencing mood swings.
- Students, particularly female students, showed higher mental health challenges in the dataset.
- These insights can inform proactive mental health strategies in academic and workplace settings.

---

## **Technologies Used**
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Seaborn, Matplotlib
- TensorFlow, Keras (for optional future neural model enhancements)

---

## **Future Work**
- Apply deep learning models (LSTM/ANN) for temporal patterns (if longitudinal data is available).
- Deploy a web-based mental health risk prediction tool using Flask or Streamlit.

---

## **Project Author**
[Akshita Ghildiyal](https://github.com/akshitaghildiyal1010)


