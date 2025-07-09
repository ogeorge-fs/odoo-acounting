# Odoo Custom Accounting Tools Module

An Odoo module that automates financial transactions and exposes a simple REST API endpoint for account balances.

## 📌 Features
- Custom financial transaction model
- Automatic journal entry creation upon transaction record
- Custom menu and views for transactions
- JSON REST API to fetch account balances
- Access control configuration

## 📚 REST API
| Method | Route                  | Description                    |
|:--------|:-------------------------|:-------------------------------|
| POST   | /api/account/balance      | Fetch balance for a given account ID |

## 📝 Installation
1. Copy `odoo_custom_accounting` folder into your Odoo addons directory
2. Update Odoo apps list
3. Install the "Custom Accounting Tools" module from the Apps menu

## 📦 Tech Stack
- Python (Odoo ORM, Controllers)
- Odoo 15/16+

## ✍️ Author
Okiri George
