# 💳 Credit Card Fraud Detection System

This project implements a **Machine Learning-based system** to detect fraudulent credit card transactions. Using the highly imbalanced `creditcard.csv` dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), a **Logistic Regression** model is trained and evaluated to classify transactions as legitimate or fraudulent.

---

## 📦 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size**: 284,807 transactions  
- **Fraud cases**: 492 (≈0.17% of total)

**Note:** The dataset is highly imbalanced and contains anonymized features (V1–V28), `Amount`, and `Time`.

---

## 🧠 Model Used

- **Logistic Regression**  
  A supervised learning algorithm used for binary classification (fraud vs. non-fraud).

---

## 🛠️ Technologies and Libraries

- **Python 3.x**
- **Pandas** – for data manipulation  
- **NumPy** – for numerical operations  
- **Scikit-learn** – model building, evaluation  
- **Matplotlib / Seaborn** – visualization  
- **Imbalanced-learn (optional)** – for resampling techniques like SMOTE

---

## 📊 Evaluation Metrics

Due to class imbalance, accuracy isn't sufficient alone. Other metrics used:

- **Confusion Matrix**
- **Precision / Recall**
- **F1-Score**
- **ROC-AUC Curve**

---

## 📂 Project Structure

CreditCardFraudDetection/
│
├── creditcard.csv # Dataset (download from Kaggle)
├── fraud_detection.ipynb # Jupyter Notebook
└── README.md # Project documentation
---

## 🔍 Key Steps

1. Data preprocessing and normalization
2. Handling imbalance (e.g., SMOTE / UnderSampling)
3. Splitting into training and test sets
4. Training Logistic Regression model
5. Evaluating with appropriate metrics
6. Visualizing performance using ROC and confusion matrix

---

## 📉 Sample Output (Confusion Matrix)

|         | Predicted No Fraud | Predicted Fraud |
|---------|--------------------|-----------------|
| Actual No Fraud | 56,000+         | 30              |
| Actual Fraud     | 40              | 400+            |

> *Note: Your results may vary based on train/test split and resampling.*

---

