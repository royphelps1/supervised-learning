# 🧠 Supervised Learning Models: Decision Tree, SVM, and ANN

![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=Jupyter)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python)
![License](https://img.shields.io/badge/License-MIT-green.svg)

This project explores three popular supervised learning models — **Decision Tree**, **Support Vector Machine (SVM)**, and **Artificial Neural Network (ANN)** — for predicting customer wait behavior at a restaurant using labeled data and model tuning techniques.

📅 **Date**: August 2, 2025  
👤 **Author**: Roy Phelps  


---

## 📂 Repository Overview


---

## 📊 Dataset & Preprocessing

- Applied one-hot encoding to categorical features.
- Used most frequent imputation for missing values.
- Standardized preprocessing across all models.

---

## 🔍 Model Summaries

### 🌳 Decision Tree
- **Best Params**: `criterion='entropy'`, `max_depth=5`
- **Weighted F1 Score**: `0.6352`
- **Accuracy**: `0.62`

### 📈 Support Vector Machine (SVM)
- **Best Params**: `kernel='linear'`, `C=0.5`
- **Weighted F1 Score**: `0.7122`
- **Accuracy**: `0.71`

### 🧠 Artificial Neural Network (ANN)
- **Best Params**: `hidden_layer_sizes=(64, 32)`, `activation='relu'`, `learning_rate=0.001`
- **Weighted F1 Score**: `0.7122`
- **Accuracy**: `0.71`

---

## 📉 Confusion Matrix (Sample)

|        | Predicted: Wait | Predicted: No Wait |
|--------|------------------|---------------------|
| **Actual: Wait**     | 12 (TP)           | 4 (FN)              |
| **Actual: No Wait**  | 3 (FP)            | 5 (TN)              |

---

## 🧪 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score (Weighted)**
- **Confusion Matrix**

---

## 🗣️ Discussion & Takeaways

- The **SVM** performed best overall in both accuracy and efficiency.
- The **ANN** matched SVM’s performance but needed deeper architecture and longer training.
- The **Decision Tree** was the easiest to interpret but underperformed in nuanced classification.

---

## 🚀 Getting Started

To run this notebook:

```bash
# Clone the repository
git clone https://github.com/yourusername/classification-models.git
cd classification-models

# Launch the notebook
jupyter notebook Roy_Phelps.ipynb
