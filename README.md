# Chicago Crime Database

## Overview
This project was developed as part of a database theory and design course and focuses on building a complete relational database system for managing and analyzing crime data. Using the Washington DC Crime Datasets 2024 from the Metropolitan Police Department, the project moves through all stages of database design — from conceptual modeling to query optimization.

## Project Phases

### Phase 1 - Entity Relationship Diagram (ERD)
- Designed an ERD to represent crime data relationships, including entities such as Crime Incident, Offense, Location, Neighborhood Cluster, Method, and Block Group.
- Defined attributes and relationships to meet the system’s data requirements.

### Phase 2 - Relational Schema & Normalization
- Converted the ERD into a Relational Schema.

### Phase 3 - Data Loading
- Created tables in PostgreSQL using the CREATE TABLE command.
- Inserted cleaned and structured dataset values into each table.
- Ensured foreign key constraints for relational integrity.

### Phase 4 - Query Development & Optimization
- Wrote SQL queries to answer analytical questions such as:
  - Which neighborhoods have the most theft incidents?
  - When does crime occur most frequently?
  - What is the most common crime per block group?
  - How many incidents involved a gun?
  - How many crimes were reported late?
- Implemented INSERT, UPDATE, and DELETE operations.
- Created Views for easier data analysis.
- Applied Indexing to improve query performance.

## Technologies Used
- PostgreSQL for database creation and querying
- SQL (DDL & DML operations)
- ERD Design Tools for conceptual modeling

## Dataset
- Source: [District of Columbia Metropolitan Police Department – Crime Data ]([https://opendata.dc.gov/](https://opendata.dc.gov/))
- Data includes crime incidents, locations, neighborhood clusters, offenses, and methods.

