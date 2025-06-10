# Employee-Performance-and-Retention-Analysis
# 📊 Employee Performance and Retention Analysis

This project analyzes employee data to uncover trends in performance and attrition using **EDA, probability & statistics, machine learning, and deep learning** techniques.

---

## 🚀 Project Objective

To build models and insights that help understand:
- Factors driving employee attrition
- Performance patterns across departments
- Predictive models for employee retention and performance

---

## 📁 Dataset

The dataset (`employee_data.csv`) contains the following features:

| Column Name       | Description                              |
|-------------------|------------------------------------------|
| EmployeeID        | Unique ID of the employee                |
| Name              | Employee name                            |
| Age               | Employee age                             |
| Department        | Department (HR, Sales, etc.)             |
| Salary            | Employee salary                          |
| YearsAtCompany    | Total years at the company               |
| PerformanceScore  | Annual performance score (numeric)       |
| Attrition         | Whether the employee left (Yes/No)       |

---

## 🧪 Project Structure

### ✅ Phase 1 - Data Exploration

- Cleaned missing values and removed duplicates
- Descriptive statistics (mean, std, etc.)
- Visualizations: heatmap, boxplot, pairplot
- Outlier detection and correlation analysis

### 🔍 Phase 2 - Probability & Statistics

- **Attrition probabilities by department**
- **Bayes’ Theorem** to compute conditional attrition probabilities
- **ANOVA** test for performance differences across departments

### 🤖 Phase 3 - Machine Learning Models

#### Attrition Prediction (Classification)
- Logistic Regression
- Accuracy: 70%, F1-Score: 0.69
- Evaluation: Precision, Recall, Confusion Matrix

#### Performance Prediction (Regression)
- Linear Regression model
- Evaluation: R² Score, Mean Squared Error

### 🧠 Phase 4 - Deep Learning (TensorFlow / Keras)

- Neural Network for performance prediction
- Neural Network classifier for attrition
- Activation functions: ReLU, Sigmoid
- Evaluation metrics: MSE, accuracy, F1

---

## 📈 Key Insights

- Departments like **Sales and Engineering** have higher attrition risk
- Performance scores **vary significantly across departments**
- Predictive models can help **identify at-risk employees** early

---

## 📊 Visualizations

- Bar chart: Attrition by department
- Boxplot: Performance by department
- Heatmap: Feature correlations
- Scatter plot: Salary vs. Performance

---


