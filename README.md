#  Life Expectancy Analysis & Predictive Modeling

---

## 1. Introduction

### 1.1 Project Overview
This project focuses on analyzing **life expectancy across countries** using historical health, economic, and social indicators. The objective is to understand the key factors influencing life expectancy and to build predictive models that estimate life expectancy based on these factors.

### 1.2 Objectives
- Analyze global life expectancy trends
- Identify key health, economic, and social drivers
- Perform exploratory data analysis (EDA)
- Build predictive models for life expectancy
- Evaluate model performance using appropriate metrics

---

## 2. Dataset Description

### 2.1 Data Source
The dataset contains country-level data collected over multiple years, covering health, demographic, and economic indicators.

### 2.2 Key Features
- Country
- Year
- Life Expectancy
- Adult Mortality
- Infant Deaths
- Alcohol Consumption
- GDP
- BMI
- Schooling
- Healthcare-related indicators

---

## 3. Data Preprocessing

### 3.1 Data Cleaning
- Handled missing values using imputation techniques
- Removed duplicate and inconsistent records
- Converted data types to appropriate formats
- Ensured numerical consistency across features

### 3.2 Feature Selection
- Selected relevant numerical features influencing life expectancy
- Removed highly correlated or irrelevant variables
- Prepared clean dataset for modeling

---

## 4. Exploratory Data Analysis (EDA)

### 4.1 Descriptive Statistics
- Computed mean, median, variance, and standard deviation
- Analyzed distribution of life expectancy across countries

### 4.2 Data Visualization
- Histograms to observe life expectancy distribution
- Scatter plots to examine relationships with GDP, schooling, and mortality
- Correlation heatmap to identify key influencing factors

### 4.3 Key Insights
- Higher GDP and schooling are associated with higher life expectancy
- Higher adult mortality and infant deaths reduce life expectancy
- Developed countries consistently show better health outcomes

---

## 5. Statistical Analysis

### 5.1 Correlation Analysis
- Strong positive correlation between schooling and life expectancy
- Negative correlation between mortality indicators and life expectancy

### 5.2 Trend Analysis
- Global life expectancy has increased steadily over time
- Developing countries show faster improvement in recent years

---

## 6. Predictive Modeling

### 6.1 Problem Type
- **Regression Problem**  
Target Variable: **Life Expectancy**

### 6.2 Models Implemented
- Linear Regression
- Multiple Linear Regression
- Random Forest Regressor
- Other regression models as applicable

---

## 7. Model Training & Evaluation

### 7.1 Train-Test Split
- Dataset split into training and testing sets
- Ensured generalization of the model

### 7.2 Evaluation Metrics
- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### 7.3 Model Performance
- Ensemble models performed better than linear models
- Random Forest achieved the highest predictive accuracy

---

## 8. Insights & Interpretation

- Economic and education indicators are strong predictors
- Healthcare quality significantly impacts life expectancy
- Predictive modeling can support policy and planning decisions

---

## 9. Conclusion

This project demonstrates how **data analysis and machine learning** can be used to understand and predict life expectancy. By combining EDA, statistical analysis, and predictive modeling, the project provides meaningful insights into global health outcomes.

---

## 10. Future Enhancements

- Include more recent and real-time data
- Apply advanced models like XGBoost
- Perform hyperparameter tuning
- Deploy the model using a web application
- Add region-wise deep-dive analysis

---

## 11. Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  End of Report
