# -Building-and-Querying-a-Relational-Healthcare-Database-Using-SQL
# Healthcare Relational Database System (SQL)

## Overview
This project demonstrates the design and implementation of a normalized relational database for a healthcare provider. It uses Python and SQLite to manage patient records, clinical visits, and lab results.

## Database Schema
The database consists of three core tables linked via Primary and Foreign keys:
1. **Patients**: Core demographic data (Name, DOB, Gender).
2. **Visits**: Billing and procedure records linked to patients.
3. **LabTestResults**: Specific clinical results linked to both visits and patients.

## Key Features
- **Normalization**: Designed to reduce data redundancy and improve consistency.
- **Relational Integrity**: Uses Foreign Key constraints to ensure data reliability.
- **Advanced Querying**: Includes examples of `INNER JOIN`, `LEFT JOIN`, and subqueries to extract operational insights.

## How to Run
1. Clone this repository.
2. Open the Jupyter Notebook in the `notebooks/` folder.
3. Run the cells to generate the SQLite database and execute the queries.

## Technologies Used
- Python
- SQL (SQLite)
- Pandas (for result visualization)
