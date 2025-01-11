# Banking-System-Using-Python

Banking System Project in Python
This project implements a Banking System using Python, showcasing Object-Oriented Programming (OOP) principles. The system includes features such as account creation, deposit, withdrawal, and balance inquiry, all implemented with a focus on extensibility and maintainability.
## 
## Key Features

**Abstract Base Class for Bank Accounts:**
    A base class BankAccount serves as the blueprint for all account types.
    Abstract methods withdraw and deposit enforce consistent behavior across derived account types.
    
**Encapsulation:**
    Private attributes such as __owner, __account_number, and __balance ensure data security.
    Getter and setter methods provide controlled access to these attributes.
    
**Polymorphism:**
    The withdraw and deposit methods are designed to be overridden by subclasses, enabling tailored functionality for different account types (e.g., savings, checking, or business accounts).
    
**Error Handling:**
    The system ensures that operations like withdrawal and deposit are validated to maintain account integrity (e.g., preventing overdrafts).
    
**Scalability:**
    The project structure allows easy addition of new account types or features without significant changes to existing code.


![Banking System Project in Python - visual selection (1)](https://github.com/user-attachments/assets/6c756ce9-b58e-4feb-abc4-ff5f538c9c36)

    
## Example Functionality
**Account Management:**
Create new bank accounts with owner information, account numbers, and initial balances.

**Transactions:**
Deposit funds into accounts.
Withdraw funds, ensuring sufficient balance.

**Data Security:**
Use of private variables for sensitive information such as account numbers and balances.


## Potential Enhancements
**Database Integration:**
Connect the system to a database for persistent storage of account information.

**Graphical User Interface (GUI):**
Develop a user-friendly interface for interacting with the banking system.

**Transaction History:**
Implement a log of all transactions for each account.

**Multi-User Support:**
Extend the system to handle multiple users with authentication features.


![Banking System Project in Python - visual selection](https://github.com/user-attachments/assets/a2469efd-1176-44ce-8640-94aceb759d39)


 **Technologies Used**
    **Programming Language:** Python
    **Key Libraries:** Built-in modules such as abc for abstract classes.


![Banking System Project in Python - visual selection (2)](https://github.com/user-attachments/assets/cc2cbaf0-07b2-41fe-b5c6-e3758fff5363)
