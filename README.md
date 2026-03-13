# Bank Management System

A Java desktop application for bank account management with GUI interfaces for common banking operations.

## Overview

A Java-based bank management system featuring graphical user interfaces for performing banking transactions including deposits, withdrawals, balance inquiries, and account management.

## Features

- **User Login** — Secure PIN-based authentication
- **Deposit** — Add funds to account
- **Withdrawal** — Withdraw funds with balance validation
- **Fast Cash** — Quick withdrawal preset amounts
- **Balance Enquiry** — Check current account balance
- **PIN Management** — Change account PIN
- **Mini Statement** — View recent transactions

## Tech Stack

- **Java** — Programming language
- **Java Swing** — GUI framework
- **JDBC** — Database connectivity

## Getting Started

### Prerequisites

- Java JDK 8+
- MySQL (or compatible database)

### Run

```bash
# Compile
javac -d out src/bank/management/system/*.java

# Run
java -cp out bank.management.system.Login
```

## Project Structure

```
└── src/bank/management/system/
    ├── Login.java              # Login screen
    ├── Pin.java                # PIN management
    ├── Deposit.java            # Deposit operations
    ├── FastCash.java           # Quick withdrawal
    ├── BalanceEnquriy.java     # Balance check
    ├── Connn.java              # Database connection
    └── MiniStatement.java      # Transaction history
```

## License

MIT
