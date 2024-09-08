

---

# Rental Management System

## Overview
The **Rental Management System** is a comprehensive tool designed to streamline the management of rental properties, tenants, and caretakers. It provides property managers with an efficient and automated solution for handling everyday tasks and operations.

## Features
- **Property Management**: Easily track and manage multiple rental properties.
- **Tenant Management**: Maintain detailed records of tenants and their lease agreements.
- **Caretaker Management**: Register and manage caretakers responsible for property maintenance.
- **Automated Notifications**: Get automated reminders for rent payments and scheduled maintenance tasks.
- **Command-Line Interface (CLI)**: User-friendly CLI for quick and seamless interaction with the system.

## Components
- **main.py**: The main entry point for running the application.
- **models.py**: Defines the database schema and relationships.
- **database.py**: Manages database connections and operations.
- **cli.py**: The Command Line Interface for user interactions.
- **create_new_db.py**: Script to create and initialize a new database.
- **bot.py**: Handles automation of tasks such as sending notifications.
- **.env**: Configuration file for environment variables.
- **Pipfile / Pipfile.lock**: Manages project dependencies.
- **rental_management.db**: SQLite database file for storing rental management data.

## Technologies Used
- **Python**: Primary programming language.
- **SQLite**: Database used to store rental management data.
- **Pipenv**: Tool for managing dependencies and virtual environments.
- **dotenv**: Manages environment variables.
- **SQLAlchemy**: ORM for database interactions.

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd rental_management
   ```

2. **Create a virtual environment and install dependencies**:
   ```bash
   pipenv install
   ```

3. **Create a `.env` file with the necessary environment variables (e.g., database credentials)**:
   ```bash
   touch .env
   # Add your environment variables in the .env file
   ```

4. **Initialize the database**:
   ```bash
   python create_new_db.py
   ```

## Running the Application
Use the Command-Line Interface (CLI) to interact with the system:
```bash
python cli.py
```

### Automation and Bots
Run the bot script to handle automated tasks and notifications:
```bash
python bot.py
```

## Workflow
1. **Initialization**: Set up the environment and initialize the database.
2. **Register Caretakers**: Use the CLI to register caretakers responsible for property maintenance.
3. **Manage Properties and Tenants**: Add properties, tenants, manage leases, and record payments.
4. **Automated Notifications**: The bot script sends automatic reminders for payments and maintenance tasks.
5. **Regular Operations**: Continue using the CLI for day-to-day management.

## Project Explanation

### Project Problem
Managing rental properties manually can lead to inefficiencies, missed payments, and disorganization. Property managers often struggle to keep track of tenants, rent schedules, and maintenance needs.

### Project Solution
The **Rental Management System** solves these issues by providing an all-in-one platform to manage tenants, properties, caretakers, and automated tasks like payment reminders. It simplifies operations and reduces the risk of errors.

### Minimum Viable Product (MVP)
The MVP includes:
- **Property Management**: Add and manage properties.
- **Tenant Management**: Store tenant information and lease agreements.
- **Caretaker Management**: Register and manage caretakers.
- **Automated Notifications**: Automatic reminders for rent payments and maintenance.
- **Command-Line Interface (CLI)**: Simple, intuitive text-based interface.
- **Database Integration**: Securely store all information in a database.

## Authors
**Griffins Mbae**  
📞 Phone: [+254 743 269 238](tel:+254743269238)  
📧 Email: [griffinskirimimbae@gmail.com](mailto:griffinskirimimbae@gmail.com)

---
