# 🔧 Predictive Maintenance System — Final Project

This project develops a predictive maintenance system to forecast potential failures in industrial equipment.  
By analyzing historical equipment data, it predicts future maintenance needs to preempt failures, reduce downtime, and improve operational efficiency.

---

## 📁 Files

- `predictive_maintenance.ipynb` — Jupyter Notebook with full analysis, models, and conclusions
- `predictive_maintenance.csv` — Dataset used in the project
- `README.md` — This documentation file

---

## 🎯 Objective

✅ Build a predictive model to identify equipment likely to fail.  
✅ Provide insights into failure patterns and recommendations for business operations.  
✅ Improve recall for rare failure events while maintaining high accuracy.

---

## 📊 Dataset

The dataset consists of 10,000 records of equipment performance and maintenance, including:

- **UDI:** Unique identifier
- **Product ID, Type**
- **Air temperature [K]**
- **Process temperature [K]**
- **Rotational speed [rpm]**
- **Torque [Nm]**
- **Tool wear [min]**
- **Target:** Binary failure indicator (0 = No Failure, 1 = Failure)
- **Failure Type**

---

## 🧰 Tools & Libraries

- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imblearn`
- Jupyter Notebook

---

## 📝 Analysis Workflow

✅ **Exploratory Data Analysis (EDA):**
- Univariate analysis: distributions of numerical and categorical features
- Bivariate & multivariate analysis: boxplots, heatmaps, pairplots

✅ **Data Preprocessing:**
- Encoding categorical variables
- Train-test split
- Feature scaling

✅ **Model Training & Evaluation:**
- Random Forest Classifier
- Cross-validation
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion matrix

✅ **Model Optimization:**
- Addressed class imbalance with SMOTE
- Hyperparameter tuning with GridSearchCV
- Re-evaluated model

---

## 📈 Results

### 🔷 Baseline Random Forest:
- **Accuracy:** 98.3%
- **Recall (Failures):** 59%
- **Precision (Failures):** 84%

### 🔷 Optimized Random Forest (with SMOTE & GridSearchCV):
- **Accuracy:** 97%
- **Recall (Failures):** 70%
- **Precision (Failures):** 48%

✅ Improved detection of rare failure events while maintaining high overall accuracy.

---

## 🔍 Insights

- Equipment failures are rare but critical to detect.
- Optimized model balances recall & precision for failures.
- Class imbalance remains a key challenge.

---

## 💡 Recommendations

- Use oversampling techniques (like SMOTE) in production.
- Further tune models & explore alternative algorithms.
- Continue feature engineering to improve predictive power.

---


## 📂 Author

Hitha Sunil

