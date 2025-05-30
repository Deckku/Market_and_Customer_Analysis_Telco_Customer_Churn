# Telecom Customer Churn Prediction Analysis 

![Telecom Customer Churn](./docs/pic_project.png) 

> "Did you know that attracting a new customer costs five times as much as keeping an existing one?"

A comprehensive data mining project analyzing and predicting customer churn in the telecommunications industry, where annual churn rates reach 15-25%.

## 👥 Project Team
- Azami Hassani Adnane
- Chegdati Chouaib 
- Bellmir Yahya
- Amcassou Hanane
- Benakka Zaid
- Lamkharbech Issa

**Supervised By:** Pr. Hosni

## 📌 Introduction
Customer churn refers to when customers discontinue their services with a company. In the highly competitive telecom industry, customers can easily switch between providers, leading to significant customer turnover. This project focuses on predicting potential churners to help companies implement targeted retention strategies.

### Why It Matters
- Retaining existing customers is 5x cheaper than acquiring new ones
- High annual churn rates (15-25%) significantly impact profitability
- Predictive analytics can help focus retention efforts on high-risk customers

## 🎯 Objectives
1. Analyze churn rate distribution
2. Identify gender-based churn patterns
3. Understand service preferences of churning customers
4. Determine profitable service types
5. Build predictive models for churn detection

## 📊 Data Analysis

### Dataset Overview
The dataset includes:
- Customer demographics (gender, age, partners, dependents)
- Service subscriptions (phone, internet, security, streaming)
- Account information (tenure, contract type, payment method)
- Billing details (monthly charges, total charges)

### Key Findings

#### 1. Customer Demographics
- Gender distribution: 49.5% female, 50.5% male
- Churn rate: 26.6% of customers switched providers
- New customers show higher churn probability

#### 2. Contract Analysis
- Month-to-month contracts: 75% churn rate
- One-year contracts: 13% churn rate
- Two-year contracts: Only 3% churn rate

#### 3. Payment Methods
##### Distribution and churn impact:

Payment Method Share Risk Level Electronic Check 33.6% Highest churn Mailed Check 22.8% Moderate Bank Transfer 21.9% Low Credit Card 21.6% Lowest churn

#### 4. Service Analysis
- Fiber optic users show higher churn rates despite popularity
- DSL users demonstrate better retention
- Higher monthly charges correlate with increased churn probability

## 🤖 Machine Learning Models

### Model Performance Comparison
Model Accuracy: 
- Voting Classifier 81.7% 
- Random Forest 81.4% 
- Logistic Regression 80.9% 
- Gradient Boosting 80.8%
- SVM 80.8%
- KNN 77.5%
- Decision Tree 72.5%

### Best Model: Voting Classifier
- Ensemble approach combining:
  - Gradient Boosting
  - Logistic Regression
  - AdaBoost
- Achieved highest accuracy: 81.7%
- Balanced precision and recall metrics

## 📈 Business Recommendations

1. **Contract Strategy**
   - Encourage longer-term contracts
   - Offer incentives for contract upgrades
   - Design special packages for month-to-month customers

2. **Payment Method Optimization**
   - Promote automatic payment methods
   - Provide discounts for bank transfer/credit card payments
   - Review electronic check payment process

3. **Service Quality**
   - Investigate Fiber optic service issues
   - Enhance technical support
   - Implement proactive maintenance

4. **Customer Retention**
   - Focus on early tenure customers
   - Develop loyalty programs
   - Regular service satisfaction surveys

## 🛠 Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Plotly
- Google Colab

## 💡 Conclusion
Customer churn significantly impacts business profitability. Our analysis shows that successful churn prevention requires:
- Understanding customer behavior patterns
- Identifying high-risk segments
- Implementing targeted retention strategies
- Improving service quality
- Building customer loyalty through personalized experiences

The project demonstrates that machine learning can effectively predict churn risk, allowing companies to take proactive measures in customer retention.

