# ATM System

A command-line based ATM system developed using Python. It allows users to create accounts, deposit money, withdraw money, and check their current balance. Account details are stored and updated automatically in an Excel file.

## Features

- Create a new bank account
- Store user details such as name, mobile number, and balance
- Deposit money into an account
- Withdraw money from an account
- Check current account balance
- Display updated balance after deposits and withdrawals
- Save account information in an Excel file
- Prevent duplicate accounts and withdrawals exceeding the available balance

## Technologies Used

- Python 3
- Python IDLE
- OpenPyXL
- Excel (`.xlsx`) for data storage

## How to Run

1. Install Python 3.
2. Install the required library:

   ```bash
   py -m pip install openpyxl
   ```

3. Download `atm.py` from this repository.
4. Open the file using Python IDLE.
5. Press **F5** or select **Run → Run Module**.
6. Follow the menu displayed in the Python Shell.

Alternatively, run the program from a terminal:

```bash
python atm.py
```

## Project Type

Console-based Python project.

## Data Storage

Account details are stored in `atm_accounts.xlsx`. The file is created automatically when the first account is created. Deposits and withdrawals update the saved balance.

## Disclaimer

This project is developed for educational purposes. It is not intended for real banking transactions.
