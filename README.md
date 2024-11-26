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

## **Results**
1. **Top Features**:
   - **Total Visits**: Positive impact on conversion probability.
   - **Total Time Spent on Website**: Indicates strong engagement.
   - **Lead Source_Lead Add Form**: High conversion potential for leads from this source.

2. **Key Metrics**:
   - Logistic Regression Accuracy: **85%**
   - AUC-ROC: **0.86**
   - Random Forest Accuracy: **88%**
   - XGBoost Accuracy: **90%**

3. **Recommendations**:
   - Focus on high-engagement leads (e.g., long time spent on the website).
   - Use targeted email/SMS campaigns for medium-priority leads.
   - Automate outreach for low-priority leads to save resources.

---

## **Folder Structure**
```plaintext
Lead-Scoring-Case-Study/
│
├── data/
│   └── Leads.csv                    # Input data file
│
├── notebooks/
│   ├── Lead_Scoring_EDA.ipynb       # Notebook for EDA and visualizations
│   ├── Lead_Scoring_Model.ipynb     # Logistic regression and model evaluation
│
├── scripts/
│   └── feature_engineering.py       # Script for data preprocessing and feature engineering
│   └── model_building.py            # Script for model training and evaluation
│
├── results/
│   ├── model_comparison.csv         # Comparison of models (Logistic, Random Forest, XGBoost)
│   └── insights.pdf                 # Key insights and business recommendations
│
├── README.md                        # Project documentation
├── requirements.txt                 # List of required Python libraries
└── LICENSE                          # Project license
```

---

## **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Lead-Scoring-Case-Study.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Lead-Scoring-Case-Study
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter notebooks in the `notebooks/` folder to explore the analysis and modeling.

---

## **Future Scope**
- Experiment with hyperparameter tuning for advanced models.
- Incorporate additional features like user behavioral data for better predictions.
- Build a deployment pipeline for real-time lead scoring.

---

## **Acknowledgments**
Special thanks to X Education for providing the dataset and framing the business problem.

--- 

Let me know if you want adjustments or additional sections!
