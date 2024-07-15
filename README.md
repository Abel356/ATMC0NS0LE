# ATMC0NS0LE
This sophisticated ATM Console Application in C# showcases a robust cardHolder class designed to simulate essential banking operations. Perfectly crafted for tech enthusiasts and future engineers, this application highlights my ability to create secure, user-friendly financial software.

**Features**:
**User Authentication:
**Secure card number and PIN verification.
Banking Operations:
Deposit: Add funds to the user's account.
Withdraw: Subtract funds from the user's account, with balance checks to prevent overdrafts.
Check Balance: Display the current account balance.
**How It Works
**Class: cardHolder

**Fields**:
String cardNum: Stores the card number.
int pin: Stores the personal identification number (PIN).
String firstName: Stores the first name of the cardholder.
String lastName: Stores the last name of the cardholder.
double balance: Stores the account balance.
Constructor: Initializes the cardHolder object with the card number, PIN, first name, last name, and balance.
Getters and Setters: Accessor methods to get and set the cardholder's details.
Main Method

printOptions: Displays the menu options for the user.
deposit: Prompts for and processes a deposit transaction.
withdraw: Prompts for and processes a withdrawal transaction, checking for sufficient balance.
balance: Displays the current balance of the cardholder.
User Interaction Flow

The user is prompted to enter their card number and PIN.
Upon successful authentication, the user can choose from deposit, withdraw, check balance, or exit.
The selected operation is performed, and the menu is displayed again until the user chooses to exit.
Getting Started
