# Python.projects
Python Projects 

# Bank Management System

## Overview

This Python project is a simple Bank Management System implemented using Object-Oriented Programming (OOP) principles. The system allows for the creation and management of bank accounts, transactions, and customer information.

## Features

- **Account Management:** Create, view, and manage bank accounts.
- **Transaction Handling:** Perform transactions such as deposits and withdrawals.
- **Customer Information:** Store and retrieve customer details.
- **Investment Portfolios:** Enable customers to invest in various financial instruments.
## Getting Started

## Usage

Describe how to use your application. Provide examples of creating accounts, making transactions, and managing customer information.

```python
# Example code snippet including investment
from bank_system import Bank, InvestmentAccount

bank = Bank()
account1 = bank.create_account("John Doe")
account2 = bank.create_account("Jane Doe")

# Regular transactions
account1.deposit(1000)
account2.withdraw(500)

# Investment transactions
investment_account = InvestmentAccount(account1, risk_tolerance='medium')
investment_account.invest(1000, 'Tech Stocks')

# Display account and investment information
print(account1.get_account_info())
print(account2.get_account_info())
print(investment_account.get_investment_info())
