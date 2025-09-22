# Task 1: Data Cleaning & Preprocessing (AI & ML Internship)

## Objective
The goal of this task was to learn how to clean and prepare raw data for Machine Learning models.

## Dataset
- **Titanic dataset** ([Kaggle link](https://www.kaggle.com/datasets/yasserh/titanic-dataset))
- Downloaded and loaded into Google Colab.

## Steps Performed
1. **Imported dataset and explored it**
   - Checked dataset shape, data types, null values, and statistical summary.

2. **Handled missing values**
   - Filled `Age` with median.
   - Filled `Embarked` with mode (if column existed).
   - Dropped `Cabin` column due to excessive missing values.

3. **Converted categorical features into numerical**
   - Applied One-Hot Encoding to `Sex` and `Embarked`.
   - Applied Label Encoding to target variable `Survived`.

4. **Scaled numerical features**
   - Standardized `Age` and `Fare` using `StandardScaler`.

5. **Detected and removed outliers**
   - Visualized outliers using boxplots.
   - Removed outliers in `Fare` using IQR method.

6. **Saved cleaned dataset**
   - Exported the final dataset as `titanic_cleaned.csv`.

## Tools Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Deliverables
- Jupyter Notebook: `task1.ipynb`
- Cleaned dataset: `titanic_cleaned.csv`
- README documentation (this file)

## Key Learnings
- How to handle missing values effectively.
- Difference between One-Hot Encoding and Label Encoding.
- Importance of feature scaling (Normalization vs Standardization).
- Detecting and removing outliers using IQR.
- Why preprocessing is critical for ML model performance.


