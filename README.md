# Refining Database Architecture

## Overview
For this assignment, I will be tasked with expanding and trimming down the database applications for the business, Curiosity Shop. Expanding on the current sales records, we will streamline the inventory and customer and employee data management tables, while maintaining the existing data on customers, employees, vendors, sales, and items.

## Project Scope
In this project, I will create entities for an Entity-Relationship Diagram (ERD) model based on the Sales and Purchased Items tables, extending them to include the Inventory and Sales and Employee data requirements. I utilized PostgreSQL for this portion.

## ERD Creation
Creating an ERD involves specifying identifiers and attributes for all entities, while justifying decisions regarding minimum and maximum cardinalities is essential for effective data modeling. I will demonstrate this skill throughout the project.

## Cardinalities
For example, there are one-to-many cardinalities and many-to-many cardinalities in the database:
- **One-to-Many:** Employee and Sales, Vendor and Inventory
- **Many-to-Many:** Customers and Sales tables
