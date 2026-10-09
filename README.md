# 📉 Customer Churn Analysis Dashboard

## 📝 Short Description

This SQL and Power BI project analyses 7,032 telecom customers to show who leaves, when they leave and why. It exists to help a retention team focus on the customers most likely to leave next.

## 🛠️ Tech Stack

  🐬 **MySQL**: data quality checks, cleaning views, analysis queries and a customer risk score
  
  📊 **Power BI**: DAX measures and a interactive dashboard

## 🗂️ Data Source

  📦 **Telco Customer Churn** on Kaggle: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## ✨ Highlights

### ❗ Business Problem

A telecom company is losing customers, and winning a new customer costs more than keeping an existing one. The business needs to know how big the churn problem is, how much revenue it costs, when and where customers leave, and which current customers are most at risk.

### 🎯 Goal of the Dashboard

  📏 Measure the churn rate and the monthly revenue lost to churn
  
  ⏳ Find when customers leave (by tenure)
  
  🔍 Find which contracts, payment methods, internet services and add-ons are linked to the highest churn
  
  🚨 Flag active customers who are most likely to leave next, using a simple risk score

### 🖼️ Walkthrough of Key Visuals

**📄 Page 1: Overview**
Headline cards (total customers, churned customers, churn rate, monthly revenue lost), a donut chart of stayed vs left, churn rate by tenure band and by contract, with slicers for contract and internet service.

**📄 Page 2: Churn Drivers**
Churn rate by payment method and internet service, plus four add-on charts (Tech Support, Online Security, Online Backup, Device Protection) that compare customers with and without each add-on.

**📄 Page 3: At-Risk Customers**
Active customers and churn rate by risk band (Low, Medium, High), the number of high-risk customers and the monthly revenue at stake, with slicers for contract and payment method.


### 💡 Business Impact and Insights

  💸 **26.6%** of customers (1,869 of 7,032) have churned, taking **30.5%** of monthly revenue with them.
  
  🆕 **New customers leave the most**: 47.68% churn in the first 12 months, against 9.51% after 4 years.

  💳 **Electronic check users churn at 45.29%**, against 15 to 19% for other payment methods.
  
  🌐 **Fiber optic customers churn at 41.89%**, more than double DSL (19.00%).
  
  🛡️ **Tech Support and Online Security** customers churn at about 15%, against about 42% without them.
  
  🚨 The risk score works: the **High band churns at 61.75%** and the Low band at 4.60%. **628 active customers** are in the High band and pay about **49.7K per month** in total.

**✅ Recommendations**
1. Focus retention effort on the first 12 months of a customer's life.
2. Offer incentives to move month-to-month customers to one-year or two-year contracts.
3. Encourage electronic check payers to switch to automatic payment.
4. Offer Tech Support and Online Security trials to at-risk customers.
