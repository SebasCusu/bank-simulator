Bank Simulator
A simple bank account simulator developed in Python using Object-Oriented Programming (OOP).

The program allows the user to manage a bank account through a simple terminal menu. Users can deposit and withdraw money while the program validates the transactions.

Features
Create a bank account with an initial balance.

Deposit money into the account.

Withdraw money from the account.

Validate deposits and withdrawals.

Prevent withdrawals when there are insufficient funds.

Handle invalid user input.

Interactive terminal menu.

Requirements
Python 3.10 or higher

This project uses only Python's standard library, so no external packages are required.

Installation
Clone the repository:

git clone https://github.com/your-username/bank-simulator.git

Move into the project directory:

cd bank-simulator

Run the program:

python main.py

How It Works
The program uses a User class to represent a bank account.

When the program starts, a user is created with an initial balance:

user1 = User(4500)

The user can then choose between three options:

1: Depositar
2: Retirar
3: Salir

Deposit
The depositar() method adds money to the account.

Deposits must be greater than zero.

Example:

Cuanto dinero quieres depositar: 500
Deposito Exitoso de 500.0
5000.0

Withdrawal
The retirar() method subtracts money from the account.

The program checks that:

The withdrawal amount is greater than zero.

The account has enough funds.

Example:

Cuanto Dinero quieres Retirar: 1000
Retiro Exitoso de 1000.0
4000.0

If the user tries to withdraw more money than available:

Fondos Insuficientes

Project Structure
bank-simulator/
│
├── main.py
└── README.md

Example
A complete interaction with the program could look like this:

1: Depositar
2: Retirar
3: Salir

Selecciona Una Opcion: 1
Cuanto dinero quieres depositar: 1000
Deposito Exitoso de 1000.0
5500.0

Selecciona Una Opcion: 2
Cuanto Dinero quieres Retirar: 750
Retiro Exitoso de 750.0
4750.0

Selecciona Una Opcion: 3

Concepts Practiced
This project was created to practice fundamental Python concepts, including:

Object-Oriented Programming

Classes and objects

Methods

Type hints

Conditional statements

while loops

Exception handling with try/except

User input

Basic financial calculations

Future Improvements
Possible improvements for future versions:

Add multiple users.

Add account numbers.

Add transaction history.

Add login authentication.

Save account information to a file or database.

Add a balance inquiry option.

Add a transfer money feature.

Improve the user interface.

Disclaimer
This project is a basic educational simulation and is not intended to represent a real banking system.
