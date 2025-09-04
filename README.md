# 📞 Telco Customer Churn Analysis  

## 📊 Live Interactive Dashboard  
[![View on Tableau Public](https://img.shields.io/badge/View-Live_Dashboard-1e4b7c?logo=tableau&style=for-the-badge)](https://public.tableau.com/app/profile/sagar.verma2557/viz/TelcoChurnAnalysis_17569809960000/Dashboard1)  

## 📖 Project Overview  
This project analyzes a telecom company's customer dataset to explore churn patterns and their relationships with customer demographics, services, contracts, and payment methods.  
The goal is to help reduce customer attrition by providing actionable insights.  

Data preparation and machine learning modeling were done in **Python**, while **Tableau** was used for interactive visualization.  

## 🛠️ Tools & Technologies  
- **Programming:** Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- **Environment:** Google Colab  
- **Visualization:** Tableau Public  
- **Version Control:** Git, GitHub  

## 📊 Dashboard Highlights  

### 🔹 Summary Metrics  
- **Churned Customers:** 1,869  
- **Total Customers:** 7,043  
- **Tenure (Sum):** 227,990 months  
- **Total Charges:** \$16,056,169  

### 🔹 Churn & Tenure with Different Aspects  
- Visual breakdown by **Dependents, Gender, and Contract type**.  
- Customers with dependents and longer contracts show lower churn.  
- Month-to-month contracts are highly correlated with churn.  

### 🔹 Churn with Respect to Payment Methods  
- Segmentation by **Internet Service, Online Backup, Online Security, and Payment Method**.  
- Customers paying via **Electronic check** and those without online security show higher churn.  

## 🔑 Key Insights  
- **Churn rate:** ~26.5% (1,869 out of 7,043 customers).  
- **Contract type:** Month-to-month contracts drive higher churn, while yearly contracts retain customers better.  
- **Services:** Lack of online security and backup services increases churn risk.  
- **Payment method:** Customers paying through **Electronic check** churn more frequently than those using credit card or automatic bank transfer.  
- **Tenure impact:** Customers with longer tenures are significantly less likely to churn.  

## 📁 Project Structure  
1. **Data Preprocessing** – Cleaning and handling missing values.  
2. **Exploratory Data Analysis (EDA)** – Identifying churn drivers.  
3. **Feature Engineering** – Encoding categorical variables, scaling numerical features.  
4. **Modeling** – Logistic Regression, Random Forest, and Gradient Boosting.  
5. **Visualization** – Tableau dashboard for stakeholder insights.  
