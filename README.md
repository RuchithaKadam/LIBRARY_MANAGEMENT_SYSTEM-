📚 Library Management System (SQL Project)

📘 Project Overview
This project is a Library Management System built using SQL that manages information related to books, publishers, borrowers, and library branches. It allows for efficient data storage, retrieval, and management of book loans, copies, and borrower records through structured database design and SQL queries.

🎯 Objectives
- To design a normalized relational database for library operations.
- To manage books, authors, borrowers, and branches systematically.
- To perform queries for analyzing borrowing trends, book availability, and branch-level operations.

🧩 Database Structure
The database includes the following tables:
- tbl_publisher – Stores publisher information.
- tbl_book – Contains details of books and their publishers.
- tbl_book_authors – Maintains author details linked to each book.
- tbl_library_branch – Stores data for each library branch.
- tbl_book_copies – Tracks the number of book copies available at each branch.
- tbl_borrower – Holds borrower information including contact details.
- tbl_book_loans – Records book loan transactions, including issue and due dates.

⚙️ Key Functionalities
- Retrieve book copies by branch and title.
- Identify borrowers with no active loans.
- Display borrower details for overdue or due books.
- Calculate total books loaned per branch.
- Identify top borrowers with more than five books issued.
- Fetch books by specific authors at a particular branch.

🧠 SQL Concepts Used:
- Database Design (DDL – CREATE, ALTER, DROP)
- Data Retrieval (DML – SELECT, JOIN, GROUP BY, HAVING)
- Constraints & Relationships (Primary Key, Foreign Key)
- Aggregate Functions (COUNT, SUM, AVG)
- Subqueries & Filtering Conditions

💻 Tools & Technologies
- Database: MySQL
- Editor/IDE: MySQL Workbench / VS Code / SQL Server Management Studio
- Language: SQL

📝 Sample Queries
- Retrieve the total copies of “The Lost Tribe” at each branch.
- Display borrowers who have borrowed more than five books.
- List all books authored by Stephen King available at the Central branch.
