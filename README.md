# 📊 Personal Finance Tracker — Excel Dashboard

An interactive Excel dashboard built on a **3000-record Personal Finance dataset** 
using Pivot Tables, Charts, and Slicers.

---

## 📁 Dataset Overview

| Column | Description |
|--------|-------------|
| `date` | Transaction date (2019–2023) |
| `user_id` | Unique user identifier |
| `monthly_income` | Total monthly earnings |
| `monthly_expense_total` | Total monthly spending |
| `savings_rate` | % of income saved (0–1) |
| `actual_savings` | Real savings amount |
| `savings_goal_met` | Goal achieved? (0=No, 1=Yes) |
| `budget_goal` | Target budget amount |
| `financial_scenario` | Economy type (inflation/normal/recession) |
| `income_type` | Salary / Freelance / Mixed |
| `credit_score` | Bank trust score (300–900) |
| `debt_to_income_ratio` | Debt vs income ratio |
| `loan_payment` | Monthly EMI amount |
| `investment_amount` | Money in stocks/mutual funds |
| `emergency_fund` | Emergency savings balance |
| `rent_or_mortgage` | Monthly rent or home loan |
| `essential_spending` | Necessary expenses (food, bills) |
| `discretionary_spending` | Non-essential expenses (shopping, dining) |
| `category` | Top spending category that month |
| `subscription_services` | Number of active subscriptions |
| `transaction_count` | Total transactions that month |
| `fraud_flag` | Fraud detected? (0=No, 1=Yes) |
| `cash_flow_status` | Positive / Neutral / Negative |
| `financial_stress_level` | Low / Medium / High |
| `financial_advice_score` | Quality of financial advice (0–100) |

- **Total Records:** 3000  
- **Total Users:** Multiple (1000–1999)  
- **Time Period:** 2019–2023 
- **Data Quality:** Clean — No missing values  

---

## 📊 Pivot Sheets — 7 Analysis Sheets

### 1️⃣ Income & Expense Analysis
- User-wise Income & Expense Summary
- Income Type Analysis (Salary vs Freelance vs Mixed)
- Cash Flow Status Summary (Positive / Neutral / Negative)

### 2️⃣ Savings Analysis
- User-wise Savings Rate & Actual Savings
- Savings Goal Met vs Not Met
- Actual Savings by Financial Scenario
- Savings Analysis by Income Type

### 3️⃣ Scenario Analysis
- Financial Scenario — Income, Credit & Savings Overview
- Stress Level Distribution by Financial Scenario
- Budget Goal & Financial Advice Score by Scenario

### 4️⃣ Category & Spending Analysis
- Discretionary vs Essential Spending by Category
- Rent & Total Expense Comparison by Category
- Spending Pattern by Income Type

### 5️⃣ Credit & Debt Analysis
- Average Credit Score by Financial Scenario
- Debt-to-Income Ratio by Income Type
- Loan Payment & Investment by Category
- High Debt Users — Debt Ratio & Credit Score

### 6️⃣ Fraud & Risk Analysis
- Fraud Count by Financial Scenario
- Fraud Detection by Income Type
- High Risk Users — Transaction & Fraud Analysis

### 7️⃣ Stress & Advice Analysis
- Financial Stress Level Distribution
- Financial Advice Score by Scenario
- Stress vs Savings — Can Advice Help?

---

## 🎯 Dashboard — Executive Overview

**Sheet Name:** `Dashboard`

An interactive single-page dashboard containing:

- 📊 **6 Charts** — Bar charts, Pie chart for quick visual insights
- 🔍 **3 Slicers** for dynamic filtering:
  - `user_id` — Filter by specific user
  - `financial_scenario` — Filter by inflation / normal / recession
  - `income_type` — Filter by Salary / Freelance / Mixed
- 📌 **Key Insights visible at a glance:**
  - Income vs Expense by Income Type
  - Cash Flow Status Distribution
  - Savings Goal Met vs Not Met (only 9% achieve goal!)
  - Credit Score & Savings Rate by Scenario
  - Stress Level vs Actual Savings
  - Fraud Risk by Income Type

---

## 🔑 Key Insights Found

- 💡 Only **9% of users** met their savings goal
- 💡 **Inflation, Normal & Recession** scenarios show similar avg savings rate **(0.23)**
- 💡 **Normal scenario** has the most users **(1739)**
- 💡 Financial stress level has minimal impact on savings rate
- 💡 Fraud cases are very low across all income types

---

## 🛠️ Tools Used

- **WPS Office / Microsoft Excel**
- Pivot Tables
- Pivot Charts
- Slicers
- Data Analysis

---

## 👨‍💻 Author

Krishna Srivastava  
Aspiring Data Analyst  
