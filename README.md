# sql_manag
TechCare Solutions Database

Project Description

This project was developed for the Relational Databases performance assessment. The objective is to transform an unstructured Excel dataset into a normalized relational database that ensures data integrity, eliminates redundancy, and provides reliable information for business decision-making.

Technologies Used

- PostgreSQL
- SQL
- Draw.io (Entity Relationship Diagram)
- Git & GitHub

Database Engine

PostgreSQL

Normalization Process

The original dataset contained duplicated records, inconsistent values, redundant information, and update anomalies.

The normalization process included:

- First Normal Form (1NF)
- Second Normal Form (2NF)
- Third Normal Form (3NF)

The final database structure removes redundancy and guarantees referential integrity.

Database Structure

The database contains the following tables:

- riwi_cities
- riwi_branches
- riwi_clients
- riwi_technicians
- riwi_equipment_categories
- riwi_equipment
- riwi_service_types
- riwi_service_orders

Each table includes primary keys, foreign keys, and integrity constraints.

Entity Relationship Diagram

The Entity Relationship Diagram (ERD) is available in the er_diagram folder.

Database Creation

1. Create the database.
2. Execute the "01_DDL.sql" script.
3. Execute the "02_DML.sql" script.
4. Execute the "03_DML.sql" script.
5. Execute the "04_QUERIES.sql" script.
6. Execute the "05_VIEWS_PROCEDURE.sql" script.

Data Loading

Data was loaded after the normalization process using SQL INSERT statements while maintaining referential integrity.

SQL Queries

The project includes the following business queries:

1. Orders handled by technician.
2. Services performed by city.
3. Services by service type.
4. Equipment with the highest maintenance frequency.
5. Clients with the largest number of service orders.
6. Orders managed by branch.

Developer Information

Full Name: Kerlys Bello

Clan: Lovelace

Repository Structure

database/
│── 01_DDL.sql
│── 02_DML.sql
│── 03_DML.sql
│── 04_QUERIES.sql
│── 05_VIEWS_PROCEDURE.sql

er_diagram/
normalization/
evidence/
original_dataset/

README.md
