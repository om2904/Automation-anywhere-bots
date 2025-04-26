The Active Loan Bot is an automation project built using Automation Anywhere that streamlines the loan management process. This bot focuses on processing active loans, filtering important loan data, and generating reports, ensuring faster decision-making and improved accuracy.

It automates the following tasks:

Reading loan data from Excel files

Filtering active loans based on criteria (e.g., status = ACTIVE)

Processing loan amounts and related information

Exporting the results to a new file or system for further processing

This project is designed to handle large datasets, minimizing manual intervention and improving operational efficiency.

## 📊 Active Loans Data
The data for this project is sourced from [BotsDNA Active Loans](https://botsdna.com/ActiveLoans/). It contains active loan records which are processed by the **Active Loan Bot**. The data is in the form of a CSV file (`active_loans.csv`) and includes essential information like loan amounts, bank details, and loan status.

## 📂 Data Structure
The dataset includes the following columns:
- **Loan_ID**: Unique identifier for each loan
- **Amount**: Loan amount
- **Bank**: Bank name
- **Status**: Loan status (e.g., ACTIVE, CLOSED)
- **Borrower_Info**: Information about the borrower
