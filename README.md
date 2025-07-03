# ChurnGuard: A Predictive Model for Customer Retention

**Author:** MOHAMMED ZAID AHMED
**Repository:** [ChurnGuard-Predictive-Model](https://github.com/Zaid2044/ChurnGuard-Predictive-Model)

ChurnGuard is a data-driven solution designed to proactively identify customers at risk of canceling their subscription ("churning"). This project showcases a full end-to-end machine learning workflow — from data cleaning and exploratory analysis to model training and performance evaluation — all inside a single Jupyter Notebook.

---

<p align="center">
  <img src="confusion_matrix.png" alt="Confusion Matrix" width="500"/>
</p>

---

## 📈 The Business Problem

In the subscription economy, customer retention is vital. Acquiring new customers can cost 5–25× more than retaining existing ones.
ChurnGuard enables a business to move from **reactive support** to **proactive success** by identifying at-risk users early and enabling strategic intervention with offers, outreach, or support.

---

## 💡 The Solution

ChurnGuard is a **binary classification model** built using Scikit-learn. It analyzes demographic data, account details, and service usage to predict churn probability.

### 🔑 Key Features

* 📊 **Exploratory Data Analysis**: Visualized churn drivers like contract type and payment method with Seaborn/Matplotlib
* 🧱 **Preprocessing Pipeline**: Used `ColumnTransformer` to apply scaling and encoding efficiently
* 🧠 **Model Training**: Built and evaluated a Logistic Regression model
* 📈 **Performance Evaluation**: Measured precision, recall, F1-score, and confusion matrix

---

## 📊 Results & Insights

The model achieved an overall **accuracy of 80.4%** on the test set.

|                  | Precision | Recall | F1-Score |
| ---------------- | :-------: | :----: | :------: |
| **No Churn (0)** |    0.83   |  0.92  |   0.87   |
| **Churn (1)**    |    0.66   |  0.45  |   0.54   |

🔎 **Interpretation**:

* Excellent at predicting loyal customers (high precision/recall for class 0)
* Moderate churn detection — improving recall for class 1 could boost retention efforts even at the cost of some false positives

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Notebook:** Jupyter (.ipynb)

---

## 🏁 Getting Started

The entire project is contained in:

```text
Churn_Prediction_Analysis.ipynb
```

### 📦 Clone the Repo

```bash
git clone https://github.com/Zaid2044/ChurnGuard-Predictive-Model.git
cd ChurnGuard-Predictive-Model
```

---

## 🚧 Future Enhancements

* Try XGBoost or Random Forests for better churn recall
* Integrate business rules or cost-sensitive learning
* Add a Flask dashboard to serve predictions live

---

## 📜 License

This project is licensed under the MIT License.

---
