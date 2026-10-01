# ATM Switching Test Case

## 👨‍💻 About Me

I am an IT professional with a background in Computer and Network Engineering (SMK TKJ), with experience in banking system implementation, ATM switching testing, SIT/UAT, API testing, SQL, Linux, and system monitoring.

## 📌 About This Project

This project contains sample test cases and documentation for ATM transaction testing in a simulated banking switching environment.

This project is created for portfolio and educational purposes using dummy data.

## 🏦 Transaction Scope

The following ATM transactions are covered:

- Cash Withdrawal
- Balance Inquiry
- Fund Transfer
- PIN Validation
- Card Validation
- Failed Transaction
- Insufficient Balance
- Invalid PIN
- Blocked Card

## 🧪 Testing Type

- Functional Testing
- Integration Testing
- Negative Testing
- Regression Testing
- SIT
- UAT

## 🔄 ATM Transaction Flow

```text
ATM
 │
 ▼
ATM Switching
 │
 ├──────────────► Core Banking
 │
 ├──────────────► Card Management System
 │
 └──────────────► Payment Network
                       │
                       ▼
                    Response

## 📋 Sample Test Cases

| Test Case | Scenario | Expected Result |
|---|---|---|
| TC001 | Successful Cash Withdrawal | Transaction Approved |
| TC002 | Insufficient Balance | Transaction Declined |
| TC003 | Invalid PIN | Transaction Declined |
| TC004 | Blocked Card | Transaction Declined |
| TC005 | Balance Inquiry | Balance Displayed |
| TC006 | Successful Fund Transfer | Transaction Approved |

## 🛠️ Tools & Knowledge

- ATM Switching
- ISO 8583
- Postman
- SQL
- Linux
- API Testing
- SIT / UAT
- Log Analysis
- Microsoft Excel

## 🔐 Disclaimer

This project is a simulation created for portfolio and educational purposes.

No real banking data, customer information, production credentials, or confidential company information is used.
