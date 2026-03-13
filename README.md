# 📊 Telco Customer Churn Prediction

A machine learning project that predicts whether a telecom customer will churn, using multiple ML models and an Artificial Neural Network (ANN). Built with Python, scikit-learn, and Keras.

## 🧠 Models Used

| Model | Type |
|-------|------|
| Logistic Regression | Classical ML |
| K-Nearest Neighbors | Classical ML |
| Decision Tree | Classical ML |
| Random Forest | Ensemble |
| ANN (Keras) | Deep Learning |

## 📁 Dataset

[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

Download `WA_Fn-UseC_-Telco-Customer-Churn.csv` and place it in the same folder as the notebook before running.

## ⚙️ What It Does

- Cleans and preprocesses raw telecom customer data
- Encodes categorical variables and scales numerical features
- Trains and compares 5 models on churn prediction
- Visualises accuracy comparison, confusion matrices, churn distribution, tenure vs churn, and top 10 feature importances
- ANN built with Keras — 2 hidden layers, sigmoid output, binary crossentropy loss

## 🚀 How to Run
```bash
# Install dependencies
pip install pandas numpy seaborn matplotlib scikit-learn tensorflow keras

# Open the notebook
jupyter notebook "ML mini project.ipynb"
```

## 📈 Visualisations Included

- Model accuracy comparison bar chart
- Confusion matrices for all 5 models
- Churn distribution count plot
- Tenure vs Churn box plot
- Top 10 feature importances (Random Forest)

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, Keras, TensorFlow, seaborn, matplotlib

## 🙋 Author

**Vikas Arunkumar** — [GitHub](https://github.com/Vikas-arunkumar) · [LinkedIn](https://www.linkedin.com/in/vikas-arunkumar-05586b2b5)
