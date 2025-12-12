Linear Regression Model – Salary Prediction Based on 10th Grade Percentage

This project builds a Machine Learning Linear Regression model to predict Salary based on Percentage in Grade 10.
The workflow includes EDA, preprocessing, training, model diagnostics, cross-validation, and final evaluation.

├── Linear_Regression_Assignment.ipynb   # Jupyter Notebook

├── dataset.csv (optional)               # Your dataset if stored separately

└── README.md                            # Documentation

1. Project Objective
To analyze whether 10th Grade Percentage can be used to predict Salary and to build a Regression Model with:
Data extraction
Statistical analysis
Visualization
Outlier detection
Model building
Diagnostics
Performan

2. Dataset Description
The dataset contains 50 entries with:ce evaluation
| Column     | Description                    |

| ---------- | ------------------------------ |

| Percentage | Student’s 10th Grade score (%) |

| Salary     | Annual Salary (₹)              | 

3. Exploratory Data Analysis (EDA)
Performed:

✔ Descriptive statistics

✔ Null value check

✔ Scatter plot (Percentage vs Salary)

✔ Correlation matrix

✔ Outlier detection using Z-score

✔ Data distribution understanding

Key Insights:
Positive correlation (0.39) between percentage and salary
Dataset contains a few outliers (425k–450k range)

4. Preprocessing
Extracted features (X = Percentage)
Extracted target (y = Salary)
Train-test split (80% train, 20% test)
Checked outliers but retained them for modeling

5. Model Used
Linear Regression
Formula learned by model:
                         Salary=m(Percentage)+b
Where:
m = Slope (Coefficient)
b = Intercept

6. Model Diagnostics Performed

✔ Best-fit regression line

✔ Residual plot (error distribution)

✔ Shapiro–Wilk Test for residual normality

✔ 5-Fold Cross-Validation (CV RMSE)

✔ Model accuracy metrics

7. Evaluation Metrics
Calculated:
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)
R² Score (Coefficient of Determination)
These measure model accuracy and error.

8. Results Summary
Model explains moderate variance (due to noisy salary data)
RMSE indicates average model error around ₹70,000
R² shows moderate predictive power
Cross-validation confirms model stability

9. Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SciPy

 How to Run This Project
1. Clone the Repository
git clone https://github.com/prajwal0995/linear-regression-project.git
cd linear-regression-project

Install Dependencies
pip install -r requirements.txt

Run the Jupyter Notebook
jupyter notebook

11. Conclusion
This project demonstrates:
How academic score correlates with salary
How to build and evaluate a regression model
How EDA and diagnostics improve understanding
How supervised learning works in real datasets

12. Author
Prajwal Badiger
Fresher | Data Science & AI | Python | SQL | ML | Power BI
