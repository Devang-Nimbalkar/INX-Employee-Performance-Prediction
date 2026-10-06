# INX Employee Performance Analysis and Prediction

## Project Overview

This project analyzes employee performance data from INX Future Inc. and builds machine learning models to predict employee performance ratings.

The goal is to identify the factors that influence employee performance and provide data-driven recommendations for improving workforce productivity.

---

## Business Problem

Organizations need to understand what factors affect employee performance so they can improve employee satisfaction, retention, and productivity.

This project aims to:

- Analyze employee performance data
- Identify key performance drivers
- Predict employee performance ratings
- Provide business recommendations

---

## Dataset Information

- Dataset: INX Future Inc Employee Performance Dataset
- Total Records: 1200
- Total Features: 28
- Target Variable: PerformanceRating

---

## Project Workflow

### 1. Data Processing

- Loaded dataset
- Checked data types
- Handled missing values
- Performed data cleaning
- Encoded categorical variables

### 2. Exploratory Data Analysis (EDA)

- Performance Rating Distribution
- Department-wise Analysis
- Overtime Analysis
- Environment Satisfaction Analysis
- Work-Life Balance Analysis
- Employee Performance Drivers

### 3. Machine Learning

Two models were developed:

#### Decision Tree Classifier

- Accuracy: 89.17%

#### Random Forest Classifier

- Accuracy: 95.00%

Random Forest achieved the highest performance and was selected as the final model.

---

## Top Factors Affecting Employee Performance

Based on Random Forest Feature Importance:

1. Employee Environment Satisfaction
2. Last Salary Hike Percentage
3. Years Since Last Promotion
4. Experience in Current Role
5. Employee Department
6. Employee Job Role
7. Employee Hourly Rate
8. Employee Age
9. Experience at Current Company
10. Distance From Home

---

## Business Recommendations

- Improve employee workplace satisfaction
- Implement performance-based salary increments
- Create transparent promotion policies
- Enhance employee engagement initiatives
- Provide role-specific training programs
- Support employee career growth opportunities

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Machine Learning Models

- Decision Tree Classifier
- Random Forest Classifier

---

## Results

| Model | Accuracy |
|---------|---------|
| Decision Tree | 89.17% |
| Random Forest | 95.00% |

---

## Conclusion

The Random Forest model achieved 95% accuracy and successfully identified the major factors affecting employee performance.

The project demonstrates how machine learning can help HR teams make data-driven decisions regarding employee performance management, promotions, and workforce development.

---

## Author

**Devang Nimbalkar**

AIML Engineer | Machine Learning Enthusiast
