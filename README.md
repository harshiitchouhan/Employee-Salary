# 🧠 Employee Salary Prediction

This project predicts employee salaries using Machine Learning models based on various demographic and professional features from the **Adult Census dataset**.

---

## 📂 Files Included

- `emp_sal_pre.ipynb` – Main Jupyter Notebook for training and evaluating the model
- `employee salary prediction.ipynb` – Alternate notebook version
- `knn_adult_csv updated.ipynb` – Experiment using KNN
- `adult 3.csv` – Cleaned dataset based on the UCI Adult Income dataset

---

## 🔍 Features Used

The dataset includes:
- Age
- Workclass
- Education
- Occupation
- Hours-per-week
- Marital-status
- Gender
- Native country
- etc.

---

## ✅ Model Workflow

1. **Data Preprocessing**:
   - Handle missing values
   - Label encoding for categorical features

2. **Exploratory Data Analysis**:
   - Summary statistics
   - Correlation heatmap

3. **Model Training**:
   - Linear Regression
   - (Optionally test: KNN, Random Forest, etc.)

4. **Evaluation**:
   - R² Score
   - Mean Squared Error
   - Prediction visualization

---

## 🛠️ How to Run

### 1. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
