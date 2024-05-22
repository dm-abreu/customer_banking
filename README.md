# Customer Banking System

## Background
Develop a customer banking system that enables users to calculate and monitor interest accrued on savings and CD accounts. This application allows users to input their account details, view interest earned, and check updated balances over a specified period.

## Files
- Module 3 Challenge files.

## Setup
- Repository: `customer_banking`
- Clone and push changes to GitHub or GitLab.

## Challenge Instructions

### Part 1: Savings Account Function
- Import the `Account` class from `Accounts.py`.
- Implement `create_savings_account` function to:
  - Instantiate `Account` with balance and interest.
  - Calculate interest: $$ interest = balance \times \left(\frac{apr}{100} \times \frac{months}{12}\right) $$.
  - Update balance with interest.
  - Return updated balance and interest earned.

### Part 2: CD Account Function
- Import the `Account` class from `Accounts.py`.
- Implement `create_cd_account` function to:
  - Instantiate `Account` with parameters.
  - Calculate and update interest earned.
  - Return updated balance and interest earned.

### Part 3: Main Function
- Import `create_cd_account` and `create_savings_account` functions.
- Prompt user for account details.
- Calculate and display interest and updated balances.

### Hints and Considerations
- Utilize functions, classes, and methods learned so far.
- Start with a single Python file, then separate functions into different files.
- Commit work regularly and ensure a detailed README.md file.

## Requirements

### Savings Account Function
- Import `Account` class correctly.
- Create `Account` instance with balance and interest.
- Calculate interest earned and update balance.
- Pass updated balance and interest to `Account` methods.
- Return updated balance and interest earned.

### CD Account Function
- Import `Account` class correctly.
- Create `Account` instance with parameters.
- Calculate interest earned and update balance.
- Pass updated balance and interest to `Account` methods.
- Return updated balance and interest earned.

### Main Function
- Prompt user for savings and CD account details.
- Print out interest earned and updated account balances.
- Call the main function to execute the program.
