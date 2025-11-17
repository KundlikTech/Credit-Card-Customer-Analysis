# 📊 Credit Card Customer Analysis
A comprehensive data analytics project focused on understanding customer spending behavior, credit score patterns, income groups, and product purchasing trends across different age segments.
This project uses multiple datasets such as customer profiles, transactions, credit limits, and payment types to derive insights for improved decision-making in the banking/credit card domain.

## 📁 Project Structure
```bash
CREDIT CARD CUSTOMER ANALYSIS/
│── data/
│    ├── avg_transactions_after_campaign.csv
│    ├── credit_profiles.csv
│    ├── customers.csv
│    └── transactions.csv
│
│── analysis.png
│── image.png
│── phase_1_banking.ipynb
│── phase_2_atliqo_banking.ipynb
│── README.md
```
---
## 📌 Project Overview

This project analyzes:

* Customer demographics
* Age-wise spending behavior
* Credit limits & credit scores
* Annual income distribution
* Payment type usage
* Product category preferences
* Effect of campaigns on customer transactions

The insights help financial institutions improve:

* ✔ Targeted marketing
* ✔ Credit scoring strategies
* ✔ Customer segmentation
* ✔ Product recommendations
---
## 🔎 Key Visual Insights

### 📌 Age Group Distribution
Understanding which age groups dominate the customer base.

### 📌 Average Annual Income by Age Group
Identifying income potential and spending capacity.

### 📌 Credit Limit & Credit Score Analysis
Helps banks optimize credit product offerings.

### 📌 Payment Method Preferences
Shows which payment channels are most used.

### 📌 Product Category Demand
Useful for targeted campaigns and retailer partnerships.

---
![Analysis](analysis.png)
![Charts](image.png)

---
## 📂 Datasets Used

| File Name | Description |
| :--- | :--- |
| **customers.csv** | Age, demographics, income, customer details. |
| **credit_profiles.csv** | Credit scores, credit limits, card type details. |
| **transactions.csv** | Transaction logs, payment types, categories. |
| **avg_transactions_after_campaign.csv** | Post-campaign customer behavior. |

---

## 🧠 Notebooks

### 🟦 phase_1_banking.ipynb

* Data cleaning
* Initial exploration
* Basic metrics

### 🟩 phase_2_atliq_banking.ipynb

* Deep analytics
* Visualizations
* Customer segmentation insights
* Statistical testing (**t-tests with alternative hypothesis**)
---
## 💻 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib / Seaborn**
* **Jupyter Notebook**

---

## 📊 Statistical Analysis

Performed **hypothesis testing** using:

* **T-test** (two-sided, larger, smaller)
    * Useful to compare mean credit limits, income differences, etc.

---

## ⭐ Key Insights Summary

* Customers aged **26–48** dominate the credit card user base.
* Highest incomes and credit limits belong to the **49–65 age group**.
* Most used payment methods include **PhonePe**, **Credit Card**, and **Cash**.
* **"Electronics," "Fashion,"** and **"Home Decor"** are top categories.
* Credit scores **improve steadily with age**.

---

## 🚀 Future Enhancements

* Build **machine learning models** for customer segmentation
* **Fraud detection** module
* **Predictive credit scoring** model
* Dashboard using **Streamlit**

---
## 🧡 Contributing

Pull requests are welcome. For major changes, please open an **issue first** to discuss what you would like to improve.

---

## 📜 License

This project is released under the **MIT License**.
