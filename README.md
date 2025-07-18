# Churn-Prediction

This repository contains a machine learning project focused on predicting customer churn using various classification algorithms. The goal is to identify customers who are likely to discontinue using a service, empowering businesses to take proactive retention measures.


## 📊 Dataset

The dataset used for this project contains customer-level data, including demographics, service usage metrics, and churn labels. Features are preprocessed and engineered before feeding into various models.

> **Note:** The dataset appears to be derived from the **Bank Customer Churn** dataset.

---

## 🧰 Technologies & Tools

* **Python 3.8+**
* **Pandas** for data manipulation
* **NumPy** for numerical operations
* **Matplotlib & Seaborn** for visualizations
* **Scikit-learn** for model building
* **XGBoost** and **CatBoost** for advanced ensemble modeling
* **Imbalanced-learn** for SMOTE oversampling

---

## 🔁 Workflow Pipeline

1. **Data Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Handling Class Imbalance with SMOTE**
5. **Model Training**: Logistic Regression, Random Forest, XGBoost, CatBoost
6. **Model Evaluation**: Accuracy, Confusion Matrix, ROC-AUC, PR Curve
7. **Hyperparameter Tuning** (where applicable)
8. **Final Model Selection**

---

## ✅ Evaluation Metrics

* **Confusion Matrix**
* **Classification Report**
* **ROC-AUC Curve**
* **Precision-Recall Curve**
* **Cross-validation**

---

### 📈 Results

* The best-performing model achieved **high recall and precision**, making it suitable for identifying potential churners effectively.
* Ensemble models like **XGBoost** and **CatBoost** outperformed traditional classifiers.

---

### 🚀 Getting Started

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/churn-prediction.git
   cd churn-prediction
   ```

2. Create a virtual environment (optional but recommended)

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the dependencies

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook

   ```bash
   jupyter notebook churn_prediction.ipynb
   ```

---

