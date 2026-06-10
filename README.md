# 💳 CodSoft Credit Card Fraud Detection

A Machine Learning project developed as part of the CodSoft Internship program to detect fraudulent credit card transactions using classification algorithms.

## 📌 Project Overview

Credit card fraud is a major challenge in the financial sector. This project builds a fraud detection system that classifies transactions as either fraudulent or legitimate using machine learning techniques.

The project includes data preprocessing, class imbalance handling using oversampling, model training, evaluation, and comparison.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Handling Imbalanced Data with Random Oversampling
- Logistic Regression Model
- Decision Tree Classifier
- Random Forest Classifier
- Performance Evaluation
- Fraud Prediction System
- Model Comparison

---

## 📊 Dataset

A sample dataset is included in this repository due to GitHub file size limitations.

Original Dataset:
https://www.kaggle.com/datasets/kartik2112/fraud-detection

Dataset Features Include:

- Transaction Amount
- Merchant Information
- Customer Information
- Geographic Details
- Transaction Time
- Fraud Label (`is_fraud`)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🤖 Models Used

### 1. Logistic Regression
A baseline linear classification model.

### 2. Decision Tree
A tree-based classification algorithm capable of learning complex decision boundaries.

### 3. Random Forest
An ensemble learning algorithm that combines multiple decision trees for improved performance and robustness.

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📂 Project Structure

```
CodSoft-Credit-Card-Fraud-Detection/
│
├── fraudTrain_sample.csv
├── Model.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/CodSoft-Credit-Card-Fraud-Detection.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells in the notebook.

---

## 📋 Results

The models were trained and compared on fraud detection performance.

Random Forest achieved the best overall performance among the tested models due to its ability to handle complex patterns and imbalanced datasets effectively.

---

## 🎯 Future Improvements

- XGBoost Implementation
- Hyperparameter Tuning
- Feature Engineering
- Real-Time Fraud Detection API
- Deep Learning Models

---

## 👨‍💻 Author

Maganpreet Singh

Project completed under the CodSoft Internship Program.

---

## ⭐ Acknowledgement

Special thanks to CodSoft for providing the opportunity to work on real-world machine learning projects.
