##Overview
Welcome to the ATM Facility Simulation, a fully functional banking application built in Java.
This project replicates the real-world operations of an ATM system, offering a smooth, secure, and interactive user experience.

##Features
> User Authentication
Login using a valid Customer ID and PIN.
Two attempts are given to enter the correct PIN, ensuring security.

>Mini Statement Generation
View a detailed mini statement showing serial number, transactions (deposit/withdrawal), credit/debit amount, and current balance.

>Deposit Funds
Deposit money into the account in multiples of 100 or 500 only.
Ensures validation to maintain realistic ATM behavior.

>Withdraw Funds
Withdraw money with available denominations of 100, 200, and 500.
Sufficient balance checking and denomination validation included.

>Account Balance Inquiry
Instantly check your available account balance at any time.

>Change PIN
Securely update your PIN to a new one after verifying your Customer ID.

>Exit System
Gracefully exit the ATM session with a thank-you message.

##Project Structure
>ATM Class:
Manages authentication, transactions, statements, and account balance.

>Uses:
LinkedHashMap to maintain transaction statements in order.
TreeMap for credential management and easy PIN updating.

>Main Class:
Contains the main() method that initiates the ATM operations.

##Technical Highlights
>OOP Concepts: Encapsulation via ATM class.

>Data Structures:
LinkedHashMap for ordered transaction history.
TreeMap for sorted credential storage.

>Error Handling:
Multiple login attempts with graceful exits on failures.
Input validation for deposits and withdrawals.

>Interactive Menu:
After every operation, users are redirected to the main menu.

>Session Management:
Clear prompts and redirection create a smooth banking session.

##Important Notes
$ Pre-registered Customer IDs and PINs are hardcoded into the system.
$ Balance is session-specific — it will reset when the application restarts.
$ Transaction security is simulated; PIN change is immediate and applies within the session.

Thank You for Banking with Us! 🏦


