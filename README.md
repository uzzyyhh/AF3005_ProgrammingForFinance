📊 AF3005 - Smart Financial Management System
This repository contains my Smart Financial Management System, developed for AF3005 - Programming for Finance at FAST-NUCES, Islamabad. The system automates financial operations using Python and IPyWidgets, allowing users to interactively perform various financial tasks.

📌 Assignment Overview
This project focuses on implementing different financial operations step by step using interactive widgets. The system includes loan assessment, risk classification, loan repayment tracking, stock monitoring, and currency exchange tracking.

🛠 Features & Functionality
✅ Loan Eligibility Assessment
-Users enter salary, employment status, and credit score.
-The system checks if the user qualifies for a loan based on predefined conditions.
-If the applicant is unemployed or earns less than PKR 50,000, the loan is rejected.
-If the credit score is 750+, the loan is approved with a 5% interest rate.
-If the credit score is between 650-749, the loan is approved with an 8% interest rate.
✅ Investment Portfolio Risk Classification
-Users enter a list of stock returns.
-The system classifies the portfolio as:
-High Risk 🔴 if any stock has a negative return.
-Medium Risk 🟠 if all returns are positive, but at least one is below 5%.
-Low Risk 🟢 if all returns are 5% or above.
✅ Automated Loan Repayment Tracker
-Users enter loan amount, interest rate, and loan term.
-The system calculates the monthly installment and tracks the remaining balance.
-A repayment schedule is displayed dynamically.
✅ Stock Market Monitoring & Alerts
-Users enter stock price trends over time.
-If the price drops significantly, an alert is triggered.
-If the price increases beyond a set threshold, a buy/sell recommendation is provided.
✅ Currency Exchange Rate Tracker & Conversion Suggestion
-Users select base and target currencies and enter exchange rates.
-The system provides latest exchange rates and suggests best times to convert money.
-Users can calculate currency conversions interactively.
🚀 How to Run This Project
1️⃣ Open the Jupyter Notebook or run it in Google Colab.
2️⃣ Enter the required financial data using interactive widgets.
3️⃣ Click buttons to process loan eligibility, portfolio risk, stock monitoring, or currency tracking.
4️⃣ View dynamic results and financial recommendations.

📥 Installation
Clone this repository:
bash
Copy
Edit
git clone https://github.com/your-username/AF3005_ProgrammingForFinance.git
Install dependencies:
bash
Copy
Edit
pip install ipywidgets
Open Jupyter Notebook and run the file:
bash
Copy
Edit
jupyter notebook
📂 Repository Structure
📁 Assignments/ – Contains the Jupyter Notebook (.ipynb) with full implementation.
📁 Datasets/ – Sample stock prices and exchange rate data for testing.
📁 Docs/ – Notes and breakdown of financial models used in the assignment.

📅 Submission Details
File Format: Jupyter Notebook (.ipynb).
Naming Convention: [Your_regno]_AF3005_Assignment1.ipynb.
Submission: Google Classroom & GitHub Repository.
🛠 Technologies Used
Python 🐍
IPyWidgets 🎛️
Jupyter Notebook / Google Colab 📒
📜 License
This project is for educational purposes only and follows the FAST-NUCES assignment policies.

💡 Feel free to explore, use, or improve this project! 🚀
