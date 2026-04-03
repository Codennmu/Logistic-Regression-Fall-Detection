# 🧠 Fall Detection using Logistic Regression

![Python](https://img.shields.io/badge/Python-3.9-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project focuses on detecting falls in elderly individuals using smartphone sensor data. Falls are a major health concern and can lead to serious physical, psychological, and financial consequences.

The objective is to build a **machine learning classification model** that can accurately distinguish between:

* **Fall events (1)**
* **Activities of Daily Living (ADL) (-1)**

---

## 🏗️ Project Pipeline

```
Raw Data → Preprocessing → Normalization → Feature Selection → Logistic Regression → Evaluation
```

---

## 📊 Dataset

* Total observations: **353**
* Total features: **21–22**
* Target variable:

  * **-1 → ADL (Normal Activity)**
  * **1 → Fall**

⚠️ **Dataset Notice:**
The dataset (`FallData_FD_KMP.xlsx`) was provided as part of a university assignment and is not publicly available. Therefore, it is not included in this repository.

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing

* Structured and cleaned dataset
* Applied normalization to scale features

### 2️⃣ Feature Selection

* Applied feature selection techniques
* Observed feature importance via model coefficients

### 3️⃣ Model Building

* Implemented **Logistic Regression**
* Applied **K-Fold Cross Validation** for robust evaluation

### 4️⃣ Evaluation Metrics

* Accuracy
* Sensitivity (Recall for Fall detection)
* Specificity

---

## 📊 Results & Performance

The model was evaluated using K-Fold Cross Validation. Below are the summarized results:

### 🔢 Model Performance

* **Number of Features Used:** 22
* **Model Accuracy:** 1.0
* **Sensitivity:** 1.0
* **Specificity:** 1.0

---

### 📌 Observations

* The model achieved **perfect accuracy (1.0)** in multiple folds.
* However, in several folds:

  * Sensitivity = 0.0
  * Specificity = 0.0

👉 This indicates that the model may have:

* Predicted only one class in certain folds
* Faced **class imbalance issues**
* Experienced **overfitting due to small dataset size**

---

### ⚠️ Important Insight

Although some folds show perfect performance:

* Accuracy = 1.0
* Sensitivity = 1.0
* Specificity = 1.0

These results may not generalize well due to:

* Limited dataset size (353 samples)
* Lack of external validation

---

## 🧠 Key Learnings

* Practical implementation of Logistic Regression
* Importance of evaluating models beyond accuracy
* Understanding class imbalance and its impact
* Application of K-Fold Cross Validation

---

## 🔥 Future Improvements

* Use **Stratified K-Fold** instead of standard K-Fold
* Handle class imbalance (SMOTE / class weights)
* Try advanced models:

  * Random Forest
  * Support Vector Machine (SVM)
  * XGBoost
* Add confusion matrix visualization
* Use a public dataset for reproducibility
* Deploy using Streamlit

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Scikit-learn

---

## 📁 Repository Structure

```
📦 fall-detection-logistic-regression
 ┣ 📜 Saad400692 A2.ipynb
 ┣ 📜 README.md
 ┗ 📜 (Dataset not included)
```

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib scikit-learn
jupyter notebook
```

---

