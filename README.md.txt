# Google Pay Expense Sharing

## Project Description
Google Pay Expense Sharing is a Python-based application that helps friends manage shared expenses. It allows users to add friends, record expenses, split bills equally or through custom amounts, calculate balances and record settlement payments.

The application uses SQLite to store transaction details permanently.

## Features
- Add and view friends
- Add shared expenses
- Split expenses equally
- Split expenses using custom amounts
- View all expenses
- Maintain individual transaction history
- Calculate individual balances
- Suggest payments between friends
- Record settlement payments
- Store data using SQLite

## Technologies Used
- Python
- SQLite
- PrettyTable
- Jupyter Notebook

## Project Structure
```text
Google_Pay_Expense_Sharing/
│
├── GooglePay_Expense_Sharing.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

## Installation and Setup

### 1. Install Python
Install Python 3 on your computer.

### 2. Install Jupyter Notebook
```bash
pip install notebook
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Project
Open the project notebook:
```bash
jupyter notebook
```

Open `GooglePay_Expense_Sharing.ipynb` and run all cells.

The SQLite database will be created automatically.

## Usage
1. Add friends to the application.
2. View the registered friends.
3. Add an expense and select the payer.
4. Select participants and choose equal or custom splitting.
5. View all recorded expenses.
6. Check individual transaction history.
7. View balance summaries.
8. Get suggested payments.
9. Record settlement payments.

## Database
The application uses SQLite with four tables:
- `users` – Stores friend details.
- `expenses` – Stores expense information.
- `expense_shares` – Stores each participant's share.
- `settlements` – Stores settlement payment details.

## Screenshots
Project screenshots are available in the `screenshots` folder.

## Note
This project is an educational expense-sharing application inspired by Google Pay. It does not perform actual money transfers or connect to Google Pay services.

## Author
Student Project – Google Pay Expense Sharing