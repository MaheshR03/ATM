# ATM Console Application

This is a simple ATM simulation program written in Python. It allows users to perform basic banking operations such as deposit, withdrawal, balance enquiry, and PIN change through a console interface.

## Features
- **Deposit:** Add money to your account (in multiples of 100).
- **Withdraw:** Withdraw money from your account (if sufficient balance).
- **Balance Enquiry:** View your current balance, transaction history, and the date/time of enquiry.
- **PIN Change:** Change your ATM PIN securely (supports leading zeros).
- **Transaction History:** See a list of all deposits and withdrawals as an array.
- **Security:** PIN is required for all operations. Incorrect PIN attempts are notified.

## Usage
1. Run the program:
   ```bash
   python atm.py
   ```
2. Enter your PIN (default is `1234`).
3. Select an option from the menu:
   - Deposit
   - Withdraw
   - Balance Enquiry
   - PIN Change
   - Exit
4. Follow the prompts for each operation.

## Example
```
Welcome to the ATM
Insert your card here
Enter your PIN: 1234
1. Deposit
2. Withdraw
3. Balance Enquiry
4. PIN Change
5. Exit
Select any one of the options: 1
Feed the cash: 500
Cash accepted
Deposit successful! New balance: 500
```

## Requirements
- Python 3.x

## Notes
- PINs are handled as strings, so leading zeros are supported.
- Transaction history is displayed as an array of amounts (+ for deposit, - for withdrawal).
- The program runs in a loop until you choose to exit.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
