# Employee Attrition Classification

This project explores employee attrition prediction using three classification models:
- Neural Network (MLP Classifier)
- K-Nearest Neighbors (KNN)
- Decision Tree

The dataset used is from Kaggle: **[IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)**

---

## 📌 Project Objective

To predict whether an employee is likely to leave the company using machine learning models and compare their performance using accuracy based on confusion matrix values.

---

## ⚙️ Models Used

| Model               | Notes                                     |
|--------------------|-------------------------------------------|
| Neural Network      | Two hidden layers, uses scaled inputs     |
| KNN (k=5)           | Distance-based, sensitive to scaling      |
| Decision Tree       | Rule-based, easy to interpret             |

All models were trained using a 50–50 train-test split and evaluated using:

> **Accuracy = (True Positives + True Negatives) / Total Test Cases**

---

## 🧪 Evaluation Summary

| Model               | Accuracy (%) | Notes                              |
|--------------------|--------------|------------------------------------|
| Neural Network      | 83.13%      | Best accuracy, but sensitive to feature scaling       |
| KNN (k=5)           | 84.35%       | Performs well overall, handles non-linear patterns   |
| Decision Tree       | 82.86%       | Most interpretable, but slightly less accurate       |

---

## 📊 Key Insights

- **Top predictors** of attrition were: `OverTime`, `JobSatisfaction`, `MonthlyIncome`, `WorkLifeBalance`.
- **Decision Trees** provided explainable rules useful for HR policy.
- **Neural Networks** outperformed others in raw accuracy.

---

## 🛠️ Tools Used

- Python 3.x
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook
- GitHub + VS Code

---

## 🔄 Future Work
- Deploy as a web app using Streamlit or Flask.

---

## 👨‍💻 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/kungfukeny1/employee-attrition-2
