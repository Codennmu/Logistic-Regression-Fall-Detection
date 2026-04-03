# 🧠 Fall Detection using Logistic Regression

> A machine learning project focused on detecting fall events in elderly individuals using smartphone sensor data.

---

## 📌 Problem Statement

Falls among elderly individuals can lead to severe health risks and long-term complications. Early detection using sensor-based systems can significantly improve response time and reduce damage.

This project builds a **classification model** to distinguish between:

* **Fall events (1)**
* **Normal daily activities (ADL) (-1)**

---

## 🏗️ Project Pipeline

```
Raw Sensor Data → Preprocessing → Feature Normalization → Feature Selection → Model Training → Evaluation
```

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing

* Cleaned and structured dataset
* Handled feature scaling using normalization techniques

### 2️⃣ Feature Engineering

* Applied feature selection techniques to reduce dimensionality
* Identified most impactful features for fall detection

### 3️⃣ Model Building

* Implemented **Logistic Regression**
* Used **K-Fold Cross Validation** to ensure robust performance

### 4️⃣ Evaluation Metrics

* ✅ Accuracy
* ✅ Sensitivity (Recall for falls)
* ✅ Specificity

---

## 📊 Results & Insights

* Logistic Regression performed effectively for binary classification
* Feature selection improved model efficiency and reduced overfitting
* Cross-validation ensured consistent performance across folds

*(Tip: You can add your actual accuracy numbers here later for stronger impact)*

---

## 📁 Repository Structure

```
📦 Logistic-Regression-Fall-Detection
 ┣ 📜 Saad400692 A2.ipynb
 ┣ 📜 README.md
 ┗ 📜 (Dataset not included)
```

---

## ⚠️ Dataset Disclaimer

The dataset used in this project (`FallData_FD_KMP.xlsx`) was provided as part of a university assignment and is not publicly available.

If you want to replicate this project, you can use similar publicly available fall detection datasets (e.g., smartphone sensor datasets).

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Scikit-learn

---

## 💡 Key Learnings

* Practical implementation of Logistic Regression
* Importance of feature selection in ML models
* Real-world application of cross-validation
* Working with health-related datasets

---

## 🔥 Future Improvements

* Replace dataset with a public dataset (e.g., Kaggle)
* Try advanced models (Random Forest, SVM, XGBoost)
* Deploy as a web app using Streamlit
* Add real-time fall detection system

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib scikit-learn
jupyter notebook
```
