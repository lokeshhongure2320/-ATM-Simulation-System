# -ATM-Simulation-System
This project is a simple ATM simulation system built using Python. The program allows users to log in using a PIN, check their account balance, and withdraw money securely using a transaction PIN.  The system also provides multiple attempts for login and transaction verification, making it similar to a basic ATM workflow.
Features

User login with PIN verification

Limited login attempts (3 tries)

Withdrawal functionality

Transaction PIN security

Balance checking before withdrawal

Minimum balance protection

Updated balance display after transaction

💳 ATM Workflow

User enters their name.

User logs in using their ATM PIN.

If the PIN is correct, the user enters the withdrawal amount.

The system asks for a transaction PIN to confirm the withdrawal.

If balance conditions are satisfied, the amount is deducted and the updated balance is displayed.

🧮 Withdrawal Logic

The withdrawal is allowed only if:

Balance
>
(
Withdrawal Amount
+
10000
)
Balance>(Withdrawal Amount+10000)

This ensures a minimum balance of ₹10,000 is maintained in the account.

🛠️ Technologies Used

Python

Conditional Statements (if-else)

Loops (for)

User Input Handling
