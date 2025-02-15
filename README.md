# 📊 AF3005 - Smart Financial Management System  

This repository contains my **Smart Financial Management System**, developed for **AF3005 - Programming for Finance** at **FAST-NUCES, Islamabad**. The system automates financial operations using **Python** and **IPyWidgets**, allowing users to interactively perform various financial tasks.  

---

## 📌 Assignment Overview  
This project focuses on implementing different financial operations step by step using **interactive widgets**.  

The system includes:  
- ✅ **Loan eligibility assessment**  
- ✅ **Investment portfolio risk classification**  
- ✅ **Automated loan repayment tracking**  
- ✅ **Stock market monitoring and alerts**  
- ✅ **Currency exchange rate tracking and conversion suggestions**  

---

## 🛠 Features & Functionality  

### ✅ Loan Eligibility Assessment  
- Users enter **salary, employment status, and credit score**.  
- The system checks if the user qualifies for a loan based on predefined conditions:  
  - If the applicant is **unemployed** or earns **less than PKR 50,000**, the loan is **rejected**.  
  - If the **credit score is 750+**, the loan is **approved at 5% interest rate**.  
  - If the **credit score is between 650-749**, the loan is **approved at 8% interest rate**.  

### ✅ Investment Portfolio Risk Classification  
- Users enter a **list of stock returns**.  
- The system classifies the portfolio as:  
  - 🔴 **High Risk** → If any stock has a negative return.  
  - 🟠 **Medium Risk** → If all returns are positive, but at least one is below 5%.  
  - 🟢 **Low Risk** → If all returns are 5% or above.  

### ✅ Automated Loan Repayment Tracker  
- Users enter **loan amount, interest rate, and loan term**.  
- The system calculates the **monthly installment** and tracks the **remaining balance**.  
- A **repayment schedule** is displayed dynamically.  

### ✅ Stock Market Monitoring & Alerts  
- Users enter **stock price trends** over time.  
- If the **price drops significantly**, an **alert is triggered**.  
- If the **price increases beyond a set threshold**, a **buy/sell recommendation** is provided.  

### ✅ Currency Exchange Rate Tracker & Conversion Suggestion  
- Users select **base and target currencies** and enter exchange rates.  
- The system provides **latest exchange rates** and suggests **best times to convert money**.  
- Users can **calculate currency conversions** interactively.  

---

## 🚀 How to Run This Project  

1️⃣ **Open the Jupyter Notebook** or run it in **Google Colab**.  
2️⃣ **Enter the required financial data** using interactive widgets.  
3️⃣ **Click buttons** to process loan eligibility, portfolio risk, stock monitoring, or currency tracking.  
4️⃣ **View dynamic results** and financial recommendations.  

---

## 📥 Installation  

Clone this repository:  
```bash
git clone https://github.com/your-username/AF3005_ProgrammingForFinance.git
