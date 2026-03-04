# CODEALPHA_ML_01  

# This project was carried out as part of my internship at CodeAlpha as a Machine Learning Intern  

## Creditworthiness Prediction using Classification Algorithms  

### Project Overview  

This project focuses on predicting an individual's creditworthiness using historical financial data. The objective is to build a robust classification model capable of distinguishing between creditworthy and non-creditworthy individuals based on structured financial indicators.

The implementation follows a structured Machine Learning workflow including data preprocessing, feature engineering, model training, and performance evaluation using industry-relevant classification metrics.

All experiments were conducted using Python and scikit-learn within a Jupyter Notebook environment.

---

### Objective  

Predict an individual's creditworthiness using past financial data.

---

### Approach  

Supervised classification algorithms were implemented and compared, including:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

The goal was to identify the model that provides the best balance between predictive performance and generalization.

---

### Key Features  

- Feature engineering from financial history  
- Handling missing values and data inconsistencies  
- Encoding categorical variables  
- Feature scaling where required  
- Model evaluation using:
  - Precision  
  - Recall  
  - F1-Score
  - Classification report

---

### Methodology  

#### 1. Data Preprocessing  

- Data cleaning and validation  
- Handling missing values  
- Encoding categorical variables  
- Feature scaling (where necessary)  
- Train-test split

  
#### 2. Model Training  

- Trained multiple classification models  
- Used consistent preprocessing pipelines  
- Compared models based on validation performance  

#### 4. Model Evaluation  

Models were evaluated using classification metrics appropriate for credit risk modeling:

- Precision (minimizing false positives)  
- Recall (capturing high-risk individuals)  
- F1-Score
- Accuracy 

Special attention was given to balancing Type I and Type II errors due to the financial risk context.

---

### Tools & Libraries Used  

- pandas  
- scikit-learn  

No additional installation is required in a standard Jupyter environment.

---

### Model  

- Type: Supervised Classification  
- Algorithms: Logistic Regression, Decision Tree, Random Forest  
- Evaluation Strategy: Metric-based comparison with emphasis on risk-sensitive metrics  

---

### How to Run  

1. Clone the repository  

```bash
git clone https://github.com/BellaKANMO/codealpha_creditScore.git
