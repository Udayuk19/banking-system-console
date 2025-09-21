# Banking Management System (Console-Based)

## Features
- User registration & login
- Change password & account locking on failed attempts
- View account balance & transaction history
- Mini-statement & transaction filtering
- Admin functions: view users, block user, reset balance, credit monthly interest
- Savings account interest calculation (4% yearly, monthly update)

## Setup Instructions
1. Install MySQL and create a database `banking_system`.
2. Import the provided `schema.sql` for `users`, `accounts`, and `transactions` tables.
3. Configure `DBConnection.java` with your MySQL credentials.
4. Ensure `JDBC` driver is added to project dependencies.

## How to Run
1. Compile all `.java` files:  
   ```bash
   javac *.java

2. Run the main class:
    ```bash
   java Main
