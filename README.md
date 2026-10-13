# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

Credit Card Fraud Detection is a machine learning project that identifies potentially fraudulent credit card transactions. The project uses classification algorithms to distinguish legitimate transactions from fraudulent ones.

The main focus is on handling imbalanced transaction data and evaluating models using meaningful fraud detection metrics.

## 🎯 Objectives

- Analyze and preprocess credit card transaction data.
- Build a Logistic Regression classification model.
- Handle class imbalance using undersampling.
- Compare Logistic Regression and Random Forest models.
- Evaluate model performance using precision, recall, F1-score, ROC-AUC, and PR-AUC.
- Visualize model performance using a confusion matrix.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Development Environment:** Google Colab
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib
- **Machine Learning:** Scikit-learn
- **Imbalanced Data Handling:** Imbalanced-learn
- **Version Control:** Git and GitHub

## 📂 Dataset

**Dataset:** [Credit Card Fraud Detection — Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset contains 284,807 transactions, including 492 fraudulent transactions.

It includes:
- `Time`: Time elapsed since the first transaction.
- `Amount`: Transaction amount.
- `V1` to `V28`: Anonymized features obtained through PCA transformation.
- `Class`: Target variable (`0` = Legitimate, `1` = Fraudulent).

The dataset is highly imbalanced because fraudulent transactions represent only a small percentage of all transactions.

## ⚙️ Project Workflow

1. **Data Loading:** Import the dataset using Pandas.
2. **Exploratory Data Analysis:** Examine transaction distributions and class imbalance.
3. **Data Preprocessing:** Separate features and target labels and split the data into training and testing sets.
4. **Model Training:** Train a Logistic Regression classifier.
5. **Imbalance Handling:** Apply class weighting and random undersampling.
6. **Model Comparison:** Evaluate Random Forest as an alternative classification model.
7. **Model Evaluation:** Calculate precision, recall, F1-score, ROC-AUC, and PR-AUC.
8. **Visualization:** Plot the confusion matrix and compare model results.

## 🤖 Machine Learning Algorithms

### 1. Logistic Regression
Used as the baseline classification model to predict whether a transaction is legitimate or fraudulent.

### 2. Logistic Regression with Undersampling
Uses random undersampling to reduce the majority class in the training data.

### 3. Random Forest
Uses an ensemble of decision trees to classify transactions and provides a comparison with Logistic Regression.

## 📊 Evaluation Metrics

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of predicted fraud cases that are actually fraudulent.
- **Recall:** Proportion of actual fraud cases detected.
- **F1-score:** Harmonic mean of precision and recall.
- **ROC-AUC:** Measures the model's ability to rank fraud cases above legitimate cases.
- **PR-AUC:** Summarizes the precision-recall trade-off across different thresholds.

Precision and recall are particularly important because false alarms and missed fraud cases have different consequences.

## 📈 Results

Model evaluation results will be documented after running the experiments.

| Model | Accuracy | Precision | Recall | F1-score | PR-AUC |
|---|---|---|---|---|---|
| Logistic Regression | To be measured | To be measured | To be measured | To be measured | To be measured |
| Logistic Regression with Undersampling | To be measured | To be measured | To be measured | To be measured | To be measured |
| Random Forest | To be measured | To be measured | To be measured | To be measured | To be measured |

*The results will be updated using actual experimental measurements.*

## 🚀 How to Run the Project

1. Clone or download this GitHub repository.
2. Open `Credit_Card_Fraud_Detection.ipynb` in Google Colab.
3. Download the dataset from Kaggle.
4. Upload `creditcard.csv` to the Colab session.
5. Install any missing dependencies as indicated in the notebook.
6. Run the notebook cells in order.
7. Review the evaluation metrics and visualizations.

## 🔮 Future Improvements

- Tune the classification threshold to balance precision and recall.
- Experiment with additional class imbalance techniques.
- Perform hyperparameter tuning.
- Compare more classification algorithms.
- Develop an interactive interface for transaction risk predictions.

## 👩‍💻 Author

**Greeshma Adabala**

GitHub: [@greeshma2267](https://github.com/greeshma2267)

---

*This project is developed for machine learning learning and portfolio purposes. It is not a production-ready financial fraud detection system.*
