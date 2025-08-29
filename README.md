# Student Performance Prediction 📊

This project applies **Linear Regression** to the **Student Performance** dataset to predict academic outcomes based on students’ study hours, previous scores, extracurricular activities, and other features.  

The goal is to build a complete machine learning workflow: data analysis, preprocessing, visualization, model training, and evaluation.

---

## 🔹 Project Workflow

1. **Data Exploration (EDA)**
   - Loaded dataset: `Student_Performance.csv`
   - Explored structure with `head()`, `describe()`, `info()`
   - Checked missing values using `isnull().sum()`
   - Visualized distributions and relationships using **Seaborn pairplots**

2. **Feature Engineering**
   - Encoded categorical feature:
     - `Extracurricular Activities` → mapped to binary (`No = 0`, `Yes = 1`)
   - Correlation analysis between features and target variable

3. **Visualization**
   - Regression plots of `Performance Index` against:
     - Previous Scores
     - Hours Studied

4. **Modeling**
   - Split dataset into **train (75%)** and **test (25%)**
   - Standardized features using **StandardScaler**
   - Applied **Linear Regression** from scikit-learn
   - Evaluated predictions with metrics:
     - MAE (Mean Absolute Error)
     - MSE (Mean Squared Error)
     - RMSE (Root Mean Squared Error)
     - R² (Coefficient of Determination)

---

## 🔹 Results

- The Linear Regression model achieved an **R² Score ≈ 0.98**, explaining ~98% of the variance in student performance.
- Hours Studied, Previous Scores, and Extracurricular Activities showed strong correlations with the target variable.

---

## 🔹 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

