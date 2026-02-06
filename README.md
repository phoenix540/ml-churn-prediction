# Churn Prediction with Logistic Regression

## Overview
This project predicts **customer churn probability** using a Logistic Regression model.  
Unlike simple yes/no predictions, it outputs **churn risk scores** between 0 and 1, allowing businesses to take proactive retention actions.

The project is implemented in a single notebook (`churn_model.ipynb`) and demonstrates:  
- Data exploration and preprocessing  
- Feature encoding and selection  
- Logistic Regression model training  
- Churn probability prediction  
- Evaluation with plots and metrics 

---

## Dataset
The notebook uses a sample dataset `data/Churn_Modeling.csv`.  
Columns include:  

- `Age` – Customer age  
- `Gender` – Male/Female  
- `Geography` – Country (Germany, Spain, France)  
- `CreditScore` – Customer credit score  
- `Balance` – Account balance  
- `Tenure` – Years with the bank  
- `NumOfProducts` – Number of products  
- `HasCrCard` – Whether customer has a credit card  
- `IsActiveMember` – Active membership status  
- `EstimatedSalary` – Estimated annual salary  
- `Exit` – 1 if the customer churned, 0 otherwise  

> If the dataset is sensitive, a **small synthetic sample** is included for demonstration purposes.

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/churn-prediction.git
