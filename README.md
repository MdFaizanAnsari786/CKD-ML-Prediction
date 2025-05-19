# Chronic Kidney Disease Prediction using Machine Learning

This project implements a robust machine learning pipeline to predict **Chronic Kidney Disease (CKD)** using a real-world synthetic dataset of 20,000 patient records. The study expands upon prior research that used only 400 samples, introducing advanced preprocessing, feature engineering, model tuning, and evaluation.

---

## 📄 Project Summary

Chronic Kidney Disease is a progressive condition that can lead to kidney failure and other severe health complications. Early detection is crucial for effective treatment. This project leverages machine learning to predict CKD from clinical features.

We evaluated multiple classifiers and determined the best-performing models based on several evaluation metrics. The research findings are also documented in a formal academic paper included in this repository.

---

## 🧠 Machine Learning Models Used

The following models were trained and compared:

- 📈 Logistic Regression
- 📊 Support Vector Machine (SVM)
- 🌲 Random Forest
- 🌿 Gradient Boosting Classifier
- ⚡ XGBoost
- 🤝 K-Nearest Neighbors (KNN)
- 🧮 Naive Bayes
- 🌳 Decision Tree

All models were tuned using **GridSearchCV** and evaluated using cross-validation.

---

## 🧪 Evaluation Metrics

Each model was assessed using:

- Accuracy
- Precision
- Recall (Sensitivity)
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📁 File Structure

```bash
├── ML_chronic_kidney_disease_code.ipynb   # Jupyter Notebook with full ML pipeline
├── synthetic_ckd_dataset_20000.csv        # Dataset (20,000 synthetic samples)
├── Research_paper.pdf                     # Research paper describing the methodology and results
└── README.md                              # Project documentation
