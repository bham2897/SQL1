# SQL1

# Stroke Prediction Dataset Management

This repository contains an SQL script designed for managing a stroke prediction dataset. The script includes operations for creating tables, inserting data, querying with aliasing, and creating views. It is intended to be used as a foundation for managing and analyzing medical data related to stroke risk.

## Features

- **Table Creation**: Define the structure for storing patient data, including health metrics and personal information.
- **Data Insertion**: Sample SQL commands for inserting data into the table.
- **Aliased Querying**: Fetch specific columns with aliases to enhance readability of the results.
- **View Creation**: Simplify data access through the creation of a dedicated view for high-risk patients.

## Prerequisites

To use this script, you will need:
- A relational database management system (RDBMS) such as PostgreSQL or SQL Server.
- Basic knowledge of SQL commands and database operations.

## Setup

1. **Database Setup**:
   - Ensure that your RDBMS is installed and running on your machine. PostgreSQL or SQL Server is recommended.
   - Create a new database, or use an existing one where you have permissions to create tables and views.

2. **Running the Script**:
   - Open your database management tool (e.g., pgAdmin for PostgreSQL, SQL Server Management Studio for SQL Server).
   - Copy the SQL script from this repository.
   - Execute the script within your database context to set up the `stroke_prediction` table, insert sample data, and create the view.

## Usage

- **Inserting Data**: Modify the `INSERT INTO` statement to include real patient data as needed.
- **Querying Data**: Use the provided SELECT statements to fetch and analyze data. Adjust the queries according to your specific analysis needs.
- **Viewing Data**: Access the `stroke_risk_patients` view to quickly get a list of patients at risk of stroke based on predefined criteria.

## Differences in SQL Flavors

- **Auto-increment Fields**:
  - PostgreSQL uses `SERIAL`.
  - SQL Server uses `IDENTITY`.
- **String Concatenation**:
  - PostgreSQL: `||`
  - SQL Server: `+`
