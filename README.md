# 💳 Predicting Credit Consumption for Customers of a Leading Bank

## 📌 Project Overview
This project focuses on analyzing customer credit card consumption patterns and developing a predictive model using **machine learning** techniques. By understanding **consumer demographics, behavior, and past transactions**, banks can offer personalized services, targeted marketing campaigns, and optimize credit card product offerings.

## 🧐 Problem Statement
Banks often struggle to analyze the **relationship between consumer characteristics and their credit card consumption patterns**. This limits their ability to:
- Customize marketing strategies
- Offer personalized financial products
- Optimize credit card offerings
- Improve customer satisfaction and loyalty

To address this, we use **machine learning models** to predict future credit card consumption based on past spending patterns.

## 🎯 Objectives
- Analyze **consumer spending behavior** using **demographics and past transactions**.
- Identify key **factors influencing credit card usage**.
- Develop predictive models to forecast **credit card consumption**.
- Provide **data-driven recommendations** for financial institutions.

## 📂 Dataset
The dataset includes:
1. **Customer Demographics** - Age, gender, and other attributes.
2. **Customer Behavioral Data** - Liabilities, assets, and transaction history.
3. **Credit Consumption Data** - Credit card spending for **April, May, and June**, and expected spending for **July, August, and September**.

## 📊 Exploratory Data Analysis (EDA)
1. **Correlation Analysis** - Examined relationships between variables.
2. **Account Type Distribution by Gender** - Identified that **current accounts** are more popular.
3. **Credit Card Usage Trends** - Compared spending by gender and account type.
4. **Age-wise Spending Behavior** - Found that the **30-40 age group** has the highest transactions.
5. **Credit vs. Debit Consumption Trends** - Observed higher credit usage among customers.

## 🚀 Machine Learning Models
Three regression models were tested to predict future credit consumption:
1. **Linear Regression** ❌ - Poor fit, failed to capture complex relationships.
2. **Decision Tree Regressor** ⚠️ - Overfitting issue, poor generalization.
3. **Random Forest Regressor** ✅ - Best performance, accurately predicted credit card consumption.

🔹 **Final Model Chosen**: **Random Forest Regressor** for its strong generalization and high accuracy.

## 🔮 Predictions & Insights
- **Targeted Campaigns**: Banks can design marketing campaigns focused on **current account holders**.
- **Personalized Offers**: Predicted spending can be used to offer **customized credit limits and rewards**.
- **Customer Segmentation**: Tailor financial products based on **age, gender, and transaction history**.

## 🛠️ Technologies Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)**
- **Jupyter Notebook**
- **Machine Learning (Random Forest, Decision Trees, Linear Regression)**
- **Data Visualization (SAS Visual Analytics, Matplotlib, Seaborn)**

# Open the Jupyter Notebook
jupyter notebook "Credit card-checkpoint.ipynb"
