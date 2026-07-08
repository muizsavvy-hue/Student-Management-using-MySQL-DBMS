# Student Management using MySQL DBMS


# 📊 Loan Risk & Customer Default Analysis

## 📌 Project Overview

Financial institutions lose millions each year due to poor lending decisions and increasing customer loan defaults. This project analyzes historical loan data from **CrediTrust**, a lending institution, to identify the key drivers of loan default, evaluate customer risk, and provide data-driven recommendations that improve lending decisions.

The project demonstrates the complete data analysis workflow, from data cleaning and exploratory analysis to risk segmentation and business recommendations.

---

## 🎯 Business Problem

CrediTrust has experienced:

- Increasing loan defaults
- Poor identification of high-risk customers
- Revenue losses from unpaid loans
- Inefficient lending decisions

The business needed an analytical solution to identify risky borrowers before loan approval.

---

## 🎯 Project Objectives

The analysis aimed to:

- Clean and prepare the dataset
- Explore customer borrowing behavior
- Identify factors associated with loan default
- Evaluate financial risk indicators
- Segment customers into risk categories
- Provide actionable business recommendations

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- SQL
- Power BI
- Python (Pandas, NumPy)
- Data Visualization

---

## 📂 Dataset Overview

The dataset contains customer loan records, including:

- Customer demographics
- Loan amount
- Income
- Employment status
- Credit score
- Loan purpose
- Previous default history
- Installment amount
- Loan status

---

# 🧹 Data Cleaning & Preparation

The following preprocessing steps were completed:

- ✅ Removed duplicate records
- ✅ Handled missing values
- ✅ Standardized categorical variables
- ✅ Corrected inconsistent formatting
- ✅ Converted data types
- ✅ Treated financial outliers
- ✅ Created new analytical features
  - Installment Burden Ratio
  - Age Groups

The cleaned dataset became more reliable for analysis and business reporting.

---

# 📈 Exploratory Data Analysis

Several exploratory analyses were conducted to better understand customer behavior.

### Key Insights

### Average Loan Amount

- Determined the average customer borrowing amount.
- Measured overall lending exposure.

### Employment Status vs Loan Amount

- Customers with stable employment generally received larger loans.

### Credit Score Distribution

- Lower credit scores were strongly associated with higher-risk borrowers.

### Loan Purpose

The most common loan purposes included:

- Personal Loans
- Business Loans

### Age Group Analysis

Middle-aged customers generally borrowed larger loan amounts.

### Income vs Loan Amount

A positive relationship existed between customer income and loan amount, although some low-income borrowers requested disproportionately large loans.

---

# ⚠️ Risk Analysis

The analysis identified the strongest indicators of customer default.

## Major Risk Factors

- Low credit score
- Previous default history
- High installment burden
- Unstable employment
- Large loans relative to income

These variables showed the strongest relationship with loan default.

---

# 👥 Customer Risk Segmentation

Customers were classified into three categories.

| Risk Level | Characteristics |
|------------|----------------|
| 🔴 High Risk | Low credit score, previous defaults, unstable employment, high repayment burden |
| 🟡 Medium Risk | Moderate financial profile |
| 🟢 Low Risk | Strong credit score, stable income, low repayment burden |

This segmentation supports better lending decisions and portfolio management.

---

# 💡 Business Recommendations

Based on the findings, the following recommendations were proposed:

### 1. Tighten Loan Approval Criteria

Apply stricter approval rules for customers with:

- Low credit scores
- Previous defaults
- Unstable employment

---

### 2. Reduce Loan Exposure

Limit loan amounts for customers with:

- Low income
- High installment burden
- Weak repayment capacity

---

### 3. Improve Customer Monitoring

High-risk customers should receive:

- Automated payment reminders
- Frequent financial reviews
- Closer repayment monitoring

---

### 4. Implement Risk-Based Lending

Offer different loan terms based on customer risk category rather than applying one approval strategy to all customers.

---

# 📊 Business Impact

Implementing these recommendations can help CrediTrust:

- Reduce loan default rates
- Improve loan recovery
- Reduce financial losses
- Increase profitability
- Improve lending decisions
- Build a healthier loan portfolio

---

# 📌 Conclusion

This project demonstrates how data analytics can improve financial decision-making by identifying high-risk borrowers before loan approval.

The analysis revealed that loan defaults are primarily influenced by:

- Credit score
- Previous default history
- Employment stability
- Repayment burden

Using customer risk segmentation and financial analysis enables lenders to reduce risk exposure and improve overall portfolio performance.

---

# 📁 Repository Structure

```
Loan-Risk-Analysis/
│
├── Dataset/
├── SQL/
├── Python/
├── Power BI/
├── Images/
├── Reports/
└── README.md
```

---

## 👨‍💻 Author

**Yusuf Abdulmuiz Gbolahan**

Senior Data Analyst | BI Analyst | Analytics Engineer

- SQL
- Power BI
- Python
- Excel
- Data Visualization
- Business Intelligence

---

⭐ If you found this project helpful, consider giving it a star.
