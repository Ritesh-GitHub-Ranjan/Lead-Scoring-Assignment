# **Lead Scoring Case Study**

## **Project Overview**
This project aims to build a **Lead Scoring Model** to help businesses prioritize high-potential leads and improve their lead conversion rate. The analysis uses a **Logistic Regression model** to predict the probability of a lead converting into a paying customer. The case study also includes exploratory data analysis (EDA), feature engineering, and advanced evaluation metrics to optimize decision-making for sales teams.

---

## **Objective**
X Education generates leads through various sources, but only a small percentage convert into paying customers. The key objectives of this project are:
1. Assign a **lead score** to each lead to prioritize high-potential leads.
2. Identify key factors contributing to lead conversion.
3. Provide actionable recommendations for business strategy improvements.

---

## **Key Features**
1. **Data Cleaning**:
   - Handled missing values, duplicates, and irrelevant features.
   - Removed non-informative levels (e.g., "Select") to improve data quality.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between features like Total Visits, Total Time Spent, and lead conversion.
   - Identified key trends, such as the importance of **engagement metrics** and **specialization domains**.

3. **Feature Engineering**:
   - Created dummy variables for categorical columns.
   - Selected the most significant features using Recursive Feature Elimination (RFE).

4. **Model Building**:
   - Built a **Logistic Regression model** to predict lead conversion probabilities.
   - Evaluated model performance using metrics like accuracy, AUC-ROC, precision, and recall.
   - Explored advanced models like **Random Forest** and **XGBoost** for comparison.

5. **Business Recommendations**:
   - Strategies to improve engagement for high-potential leads.
   - Recommendations for prioritizing leads during peak and low-sales periods.

---

## **Technologies Used**
- **Python**: Data analysis, modeling, and visualizations.
- **Libraries**:
  - `pandas` and `numpy`: Data manipulation and preparation.
  - `matplotlib` and `seaborn`: Visualizations for EDA.
  - `sklearn`: Machine learning model building and evaluation.
  - `statsmodels`: Statistical analysis and logistic regression.
  - `xgboost`: Advanced classification model.

---

## **Project Workflow**
1. **Data Understanding and Cleaning**:
   - Inspected data for missing values and outliers.
   - Dropped irrelevant columns and handled categorical variables.
2. **EDA**:
   - Explored key features and visualized correlations.
   - Identified the most impactful variables for conversion.
3. **Modeling**:
   - Built a Logistic Regression model.
   - Evaluated performance using AUC-ROC, precision, and recall.
   - Compared performance with Random Forest and XGBoost.
4. **Business Insights**:
   - Recommended strategies to optimize lead conversion based on model outputs.

---

## **Future Scope**
- Experiment with hyperparameter tuning for advanced models.
- Incorporate additional features like user behavioral data for better predictions.
- Build a deployment pipeline for real-time lead scoring.

---

## **Acknowledgments**
Special thanks to X Education for providing the dataset and framing the business problem.

--- 
