# Customer Churn Prediction Using Logistic Regression

![Customer Churn Dashboard](https://github.com/wainaina-peter/Customer-Churn-Prediction-using-Logistic-Regression/assets/80960028/2038e2e5-a14f-44a1-bd7b-1799f2d7a14e)

## Project Overview

Customer churn is an important business problem, especially for companies in the telecommunications industry. When customers stop using a company's services, the business can lose recurring revenue and may need to spend additional money to acquire new customers.

This project focuses on analyzing customer data to understand the factors that may influence customer churn and building a **Machine Learning model using Logistic Regression** to predict whether a customer is likely to leave the company.

The project combines **Data Analysis, Exploratory Data Analysis (EDA), Machine Learning, and Business Intelligence**. In addition to the prediction model, Power BI dashboards were created to make the findings easier to understand and support business decision-making.

The main goal is to use historical customer information to identify patterns associated with churn and provide useful insights that can help a telecom company improve customer retention.

---

# 1. Business Understanding

Customer churn refers to customers stopping their relationship with a company or no longer using its products or services.

Churn prediction is the process of using customer information and historical data to identify customers who may be likely to leave in the future.

This is particularly important for businesses that depend on recurring revenue, such as telecommunications companies and subscription-based services. Keeping existing customers can be more cost-effective than constantly trying to acquire new customers.

By identifying customers who have a higher likelihood of churning, a company can take action earlier. For example, the company could provide personalized offers, improve customer support, introduce better service packages, or provide incentives to encourage customers to remain with the company.

This project therefore focuses on answering questions such as:

- What characteristics are associated with customer churn?
- Which services or subscription types have higher churn?
- Does the length of time a customer has been with the company affect churn?
- How do payment methods relate to customer churn?
- How do contract types affect customer retention?
- Can customer information be used to predict whether a customer is likely to churn?

---

# 2. Data Understanding

The dataset used in this project was obtained from Kaggle.

**Dataset:** Telco Customer Churn

**Source:**  
https://www.kaggle.com/datasets/puja19/telcom-customer-churn

The dataset contains information about **7,043 customers** and **21 columns**.

The variables include information about:

- Customer demographics
- Gender
- Senior citizen status
- Partners and dependents
- Tenure
- Phone services
- Internet services
- Contract type
- Payment method
- Monthly charges
- Total charges
- Customer churn status

The main target variable is **Churn**, which indicates whether a customer has left the company.

The dataset provides a good opportunity to investigate customer behavior and identify patterns that may be associated with churn.

---

# 3. Problem Statement

The telecommunications industry faces the challenge of customers leaving their service providers.

High customer churn can negatively affect revenue and long-term business growth. However, simply knowing that customers are leaving is not enough. A company needs to understand which customers are more likely to leave and what factors may be associated with their decision.

The problem addressed in this project is therefore to analyze customer data, identify patterns related to churn, and develop a machine learning model that can predict whether a customer is likely to churn.

The predictions can then be used to support customer retention strategies and help the business take action before customers leave.

---

# 4. Main Objective

The main objective of this project is to **analyze customer churn patterns and develop a machine learning model that can predict customers who are likely to leave a telecommunications company.**

The insights from the analysis can help the company develop strategies aimed at improving customer retention and reducing churn.

---

# 5. Specific Objectives

The project has the following objectives:

- Review and understand the telecom customer dataset.
- Identify the factors that may be associated with customer churn.
- Clean and prepare the data for analysis and machine learning.
- Check the dataset for missing values, inconsistent values, and other data quality issues.
- Perform Exploratory Data Analysis (EDA) to identify trends and patterns.
- Analyze the relationship between customer characteristics and churn.
- Prepare the data for machine learning.
- Build a Logistic Regression classification model.
- Evaluate the performance of the model using appropriate classification metrics.
- Identify customers who may be at higher risk of churning.
- Create Power BI dashboards to communicate the findings.
- Provide business recommendations based on the analysis.

---

# 6. Data Cleaning and Preparation

Before building the machine learning model, the dataset was reviewed and prepared for analysis.

The data preparation process included:

- Checking the structure and data types of the dataset.
- Identifying missing or blank values.
- Checking for inconsistent values.
- Converting variables into appropriate data types.
- Preparing categorical variables for machine learning.
- Reviewing numerical variables.
- Separating the target variable from the input variables.
- Preparing the data for model training and testing.

Data preparation is an important part of the project because the quality of the input data can affect the performance of the machine learning model.

---

# 7. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to better understand the dataset and identify patterns related to customer churn.

Different customer characteristics were compared against the **Churn** variable to understand how they may be related to customers leaving the company.

The analysis looked at areas such as:

- Customer tenure
- Contract type
- Monthly charges
- Total charges
- Internet service
- Payment method
- Phone service
- Paperless billing
- Partner status
- Dependents
- Senior citizen status
- Other customer service features

Visualizations were used to make these relationships easier to understand and to identify trends that may not be immediately visible from the raw data.

The EDA helped provide a better understanding of the customer base before developing the machine learning model.

---

# 8. Machine Learning Model

## Logistic Regression

The machine learning model used in this project is **Logistic Regression**.

Logistic Regression is a classification algorithm commonly used when the outcome has two possible classes.

In this project, the model predicts whether a customer:

- **Will churn**
- **Will not churn**

The model was trained using historical customer information and the corresponding churn outcome.

One advantage of Logistic Regression is that it is relatively simple and interpretable. This makes it useful for business problems where understanding the factors behind predictions is also important.

The general machine learning workflow used in this project was:

```text
Customer Dataset
       ↓
Data Cleaning
       ↓
Data Preparation
       ↓
Exploratory Data Analysis
       ↓
Feature Preparation
       ↓
Train/Test Split
       ↓
Logistic Regression
       ↓
Model Evaluation
       ↓
Churn Prediction
```
# 9. Model Evaluation

The performance of the Logistic Regression model was evaluated using different classification metrics.

These include:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Recall

Recall is particularly important for this project because the business is interested in identifying customers who are likely to churn.

A model with good recall is better at identifying customers who actually churned.

In a customer retention scenario, failing to identify a customer who is likely to leave can mean that the company loses an opportunity to take action.

Therefore, **recall was considered an important metric when evaluating the model**, alongside the other classification metrics.


# 10. Business Insights

The analysis revealed several patterns in the customer data that can help the business better understand customer churn.

Some customer groups showed different churn behavior based on factors such as:

- Contract type
- Payment method
- Tenure
- Monthly charges
- Internet service
- Partner and dependent status
- Billing preferences
- Additional services

These patterns can help the company understand which customer groups may require more attention and where customer retention strategies could be focused.

It is important to note that these relationships are based on patterns observed in the dataset and should be further investigated before being used as direct business rules.


# 11. Recommendations

Based on the analysis of the different variables against the **Churn** target variable, the following recommendations can be considered:

### 1. Encourage Longer-Term Contracts

Customers with longer-term contracts showed lower churn compared with some customers on shorter contracts.

The company could encourage customers to move to longer contracts by offering suitable incentives, discounts, or additional benefits.

### 2. Provide Attractive Bundle Packages

The company could introduce or improve bundled service packages that combine multiple services.

Bundling services may provide customers with more value and could encourage them to continue using the company's services.

### 3. Offer Incentives for Longer Subscription Periods

Customers who commit to longer subscription periods could be offered incentives such as discounts or additional services.

This could encourage customers to remain with the company for longer periods.

### 4. Improve Customer Retention for High-Risk Customers

The churn prediction model can be used to identify customers who may be at higher risk of leaving.

The company could then provide targeted retention offers or customer support before those customers decide to leave.

### 5. Review Payment and Billing Options

The analysis showed differences in churn behavior across payment and billing methods.

The company should continue monitoring these patterns and make sure that customers have convenient and reliable payment options.

### 6. Focus on Customer Experience

Customer retention should not only depend on discounts. The company should also focus on service quality, customer support, reliability, and providing useful services that encourage customers to stay.


# 12. Power BI Dashboards

Power BI was used to create interactive dashboards for analyzing and presenting the customer churn data.

The dashboards provide a visual summary of customer information and help users explore the factors associated with churn.

The dashboards focus on areas such as:

- Total customers
- Churned customers
- Customer churn rate
- Customer demographics
- Contract types
- Payment methods
- Internet services
- Monthly charges
- Tenure
- Customer service features

The dashboards make it easier for business users to identify trends and compare different customer groups without having to work directly with the raw dataset.

## Dashboard Preview

![Power BI Dashboard](https://github.com/wainaina-peter/Customer-Churn-Prediction-using-Logistic-Regression/assets/80960028/58bb1d0b-977c-4dac-8931-3d8e3a0bc3bb)

![Power BI Dashboard](https://github.com/wainaina-peter/Customer-Churn-Prediction-using-Logistic-Regression/assets/80960028/b384d499-750f-4d91-9b4d-1e18bdcd0309)

[View the Power BI Dashboards](https://github.com/wainaina-peter/Customer-Churn-Prediction-using-Logistic-Regression/files/14121594/TelecomBIdashboards.pdf)


# 13. Tools and Technologies

The following tools and technologies were used in this project:

- **Python** – Data analysis and machine learning
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine learning and model evaluation
- **Jupyter Notebook** – Data analysis and model development
- **Power BI** – Interactive dashboards and business intelligence
- **GitHub** – Project documentation and version control


# 14. Project Structure

```text
Customer-Churn-Prediction-using-Logistic-Regression/
│
├── Customer Churn Prediction.ipynb
├── README.md
```
