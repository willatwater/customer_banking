# Homework 3

# Customer Banking Program

This program calculates the interest earned on savings and certificate of deposit (CD) accounts over a specified period, using user-defined balances, interest rates, and maturity periods. It updates the account balances with the earned interest and displays the final results with proper formatting.

## Files

1. **Account.py**: Contains the `Account` class, representing a general bank account with methods to handle balance and interest.
2. **savings_account.py**: Defines the `create_savings_account` function, which creates a savings account instance, calculates interest earned, updates the account balance, and returns the updated balance and interest.
3. **cd_account.py**: Defines the `create_cd_account` function, similar to `create_savings_account`, but specifically for a CD account.
4. **customer_banking.py**: The main script where the program runs. This script prompts the user for input, calls the functions to calculate interest for both savings and CD accounts, and displays the results.

## Requirements

- **Python 3.x** is required to run this program.

## Setup and Installation

1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```bash
   cd customer_banking
   ```

## Usage

Run the program by executing the following command:

```bash
python customer_banking.py
```

### Example Workflow

1. **Savings Account**: Enter the balance, interest rate, and maturity period in months.
   - Example Input:
     ```
     Enter savings account balance: 1000
     Enter savings account interest rate (X.XX): 2.5
     Enter savings maturity in months: 12
     ```
   - Example Output:
     ```
     Savings account will earn $25.00 in interest.
     Balance after earned interest will be $1,025.00.
     ```

2. **CD Account**: Enter the balance, interest rate, and maturity period in months.
   - Example Input:
     ```
     Enter CD account balance: 5000
     Enter CD account interest rate (X.XX): 3.0
     Enter CD account maturity in months: 12
     ```
   - Example Output:
     ```
     CD account will earn $150.00 in interest.
     Balance after earned interest will be $5,150.00.
     ```

## Function Overview

- **create_savings_account(balance, interest_rate, months)**:
  - Creates a savings account, calculates interest earned based on user input, updates the balance, and returns the new balance and interest earned.

- **create_cd_account(balance, interest_rate, months)**:
  - Creates a CD account, calculates interest, updates the balance, and returns the updated balance and interest earned.