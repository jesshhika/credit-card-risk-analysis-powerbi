# Credit Card Financial Dashboard (Power BI)

## 📌 Project Overview
This project focuses on analyzing credit card customer and transaction data to gain insights into spending behavior, credit utilization, delinquency risk, and revenue generation. The dashboard is built using **Power BI** and is designed to support **business decision-making** for financial institutions.

The solution provides a clear view of customer behavior, identifies high-risk customers, and highlights opportunities for improving credit management strategies.

---

## 🎯 Objectives
- Analyze customer spending patterns across categories
- Measure credit utilization and outstanding balances
- Identify delinquent and high-risk customers
- Evaluate revenue from interest and annual fees
- Enable interactive analysis using slicers and filters

---

## 🧾 Dataset Description
The project uses two datasets:

### 1️⃣ Customer Dataset (`customer.csv`)
Contains customer demographic and profile information:
- Customer ID
- Age, Age Group, Gender
- Education Level, Marital Status
- Occupation, Annual Income
- Home Owner, Car Owner, Personal Loan
- Customer Satisfaction Score
- Contact Method

### 2️⃣ Credit Card Dataset (`credit_card.csv`)
Contains transaction and credit behavior data:
- Customer ID
- Week Start Date, Quarter, Year
- Credit Limit, Revolving Balance
- Transaction Amount and Count
- Expense Type, Transaction Mode
- Card Category
- Delinquent Account Indicator
- Interest Earned, Annual Fees
- Activation Status and Acquisition Cost

---

## 🏗️ Data Model
- **Star Schema**
- Customer table → Dimension
- Credit Card table → Fact
- One-to-Many relationship using `Customer ID`

This structure ensures accurate aggregations and scalable analysis.

---

## 📊 Dashboard Pages

### 📄 1. Executive Overview
- Total Spending
- Total Credit Limit
- Credit Utilization %
- Total Revenue
- High Risk Customers
- Spending trend over time
- Spending by category and card type

### 📄 2. Spending & Customer Behavior
- Spending by expense category
- Spending by card category
- Transaction volume by age group
- Transaction mode distribution
- Income vs spending analysis

### 📄 3. Credit Risk & Delinquency
- Delinquent accounts and delinquency rate
- High utilization and high-risk customers
- Credit utilization by age group
- Delinquency by demographics
- High-risk customer detail table with filters

---

## 📐 Key Metrics (DAX Measures)
- Total Spending
- Total Credit Limit
- Credit Utilization %
- Total Revolving Balance
- Delinquency Rate %
- High Utilization Customers
- High Risk Customers
- Total Revenue (Interest + Fees)
- Activation Rate %

Advanced DAX techniques such as `CALCULATE`, `FILTER`, and context transition were used for accurate risk metrics.

---

## 💡 Business Insights
- Customers aged 25–40 contribute the highest transaction volume
- High credit utilization strongly correlates with delinquency
- Certain card categories generate higher revenue but carry more risk
- Digital transaction modes dominate overall usage
- A small segment of customers contributes disproportionately to credit risk

---

## 📈 Recommendations
- Introduce early warning alerts for high-utilization customers
- Offer flexible repayment options to reduce delinquency
- Optimize credit limits based on spending and payment behavior
- Target high-income, low-risk customers for premium card upgrades
- Strengthen monitoring of repeat delinquent customers

---

## 🛠️ Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- CSV datasets

---

## 🚀 How to Use
1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Refresh data if required
4. Use slicers to explore insights interactively

---

## 📌 Author
**[Your Name]**  
Aspiring Data Analyst / Business Intelligence Developer

---

## 📜 License
This project is for educational and portfolio purposes.
