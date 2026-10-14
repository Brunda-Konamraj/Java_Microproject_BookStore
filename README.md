# Online Book Store Management System

A Java-based e-commerce platform developed for publishing companies to manage book catalogs, customer purchases, inventory stock, and secure orders. This project satisfies multiple Course Outcomes (CO1 to CO5) by integrating Object-Oriented Programming, Exception Handling, Multithreading, Collection Frameworks, and JDBC Database Connectivity.


##  Course Outcomes Addressed (CO1 - CO5)
* **CO1 & CO2 (OOP & Interfaces):** Built using robust object-oriented principles, utilizing classes (`Book`, `Author`), inheritance, and custom interfaces (`Sellable`).
* **CO3 (Exception Handling & Multithreading):** Implements safe user inputs and database connection exception handling, along with a separate thread (`OrderProcessorThread`) to simulate secure, non-blocking order and payment processing.
* **CO4 (Collections & Streams):** Uses Java Collection Framework (`List`, `HashMap`) for shopping carts and Java Stream APIs for fast book searching and filtering.
* **CO5 (Database Connectivity):** Integrates relational database connectivity using JDBC (SQLite) to maintain persistent data and automatically update inventory stock upon purchase.


##  Tech Stack
* **Language:** Java (JDK 8 or higher)
* **Database:** SQLite (Relational Database)
* **Driver:** SQLite JDBC Driver


##  Project Structure
```text
├── BookStoreApp.java       # Main application containing all business logic, OOP classes, and JDBC integration
├── bookstore.db            # Local SQLite database (auto-generated upon first run)
└── README.md               # Project documentation
