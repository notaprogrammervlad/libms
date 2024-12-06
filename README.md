# Library Management System

A robust and user-friendly system for managing books, members, librarians, and loans in a library environment. The system includes features for book reservations, fine calculations, and librarian authentication.

---

## Features

### General
- **Book Management**: Add, update, and categorize books with detailed information.
- **Member Management**: Register members and track their membership expiry dates.
- **Publisher Management**: Record publisher details for books.

### Operations
- **Loan Management**: Issue and return books, calculate overdue fines.
- **Reservation System**: Allow members to reserve books and manage reservation statuses.

### Authentication
- **Librarian Login**: Secure login system for librarians with unique usernames and hashed passwords.

---

## Tech Stack

### Backend
- **Programming Language**: C#
- **Database**: MySQL with ODBC connection

### Frontend
- **User Interface**: Desktop-based application (e.g., Windows Forms or WPF)

### Tools & Libraries
- **ODBC (Open Database Connectivity)**: For connecting C# to the MySQL database.
- **Password Hashing Library**: For secure password storage (e.g., BCrypt, if implemented).
- **PlantUML**: To design and visualize the system's database structure.

### Testing & Debugging
- **SQL Clients**: Tools like MySQL Workbench for managing and testing database queries.
- **Visual Studio**: IDE for C# application development.

---

## How to Use

### Prerequisites
1. MySQL Server installed and configured.
2. Visual Studio installed with C# development environment.
3. ODBC driver installed for MySQL.

### Setup Instructions
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-repo/library-management-system.git
