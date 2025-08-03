# 🏦 Banking Risk Analytics Dashboard – Power BI

## 📌 Overview
A Power BI dashboard designed to help banks identify high-risk clients and make informed lending decisions using customer profiles and financial data.

## 📁 Dataset
Multiple relational tables:
- Clients - Banking
- Banking Relationship
- Gender
- Investment Advisor
- Period

## 🧹 Data Processing
- **Engagement Days**: Time spent by client with the bank
- **Income Band**: Classified as Low (< ₹100k) and Mid (< ₹300k)
- **Processing Fees**: Based on Fee Structure (High: 5%, Medium: 3%, Low: 1%)

## 📊 Key Metrics (DAX)
- `Total Clients = DISTINCTCOUNT(Client ID)`
- `Total Loan = Bank Loan + Business Lending + Credit Card Balance`
- `Total Fees = SUMX(..., Total Loan * Processing Fees)`

## 📈 Dashboards
- **Home**
- **Loan Analysis**
- **Deposit Analysis**
- **Summary**

## 🚀 Insights
- Detect high-risk clients
- Analyze loan & deposit trends
- Identify client engagement patterns

## 🛠 Tools
- Power BI
- DAX
- Relational Modeling




