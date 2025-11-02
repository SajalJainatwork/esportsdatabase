

![esports](https://github.com/user-attachments/assets/853d9c86-a3b5-4e40-8fd0-0a6132adbdcf)

This project involves the creation and analysis of a MySQL Relational Database designed to manage and track the complex operations of an eSports organization. It is a comprehensive demonstration of Database Design, SQL Implementation, Data Population, and Querying.

Here is a detailed note of the project's purpose, scope, and technical features

📝 eSports Database Project
🎯 Project Title
eSports Management System: Relational Database Design & Implementation (MySQL)

Comprehensive Database Modeling for an eSports Organization (MySQL Workbench)

SQL Schema Development and Data Analysis for eSports Operations

🔑 Project Overview & Scope
The core goal of this project was to model the entire organizational structure and operations of a modern eSports team into a robust, normalized relational database. The system is designed to track four primary domains:

Corporate Operations: Managing Employees, Departments, and Buildings (HQ, Arena, Warehouse).

eSports Core: Tracking Video Games, Leagues, Teams, Players, and Coaches.

Revenue & Inventory: Managing Sponsorships, Merchandise inventory, Vendors, and Customer Orders.

Marketing & Media: Tracking Content Creators, Social Media platforms, and Advertisements.

🛠️ Technical Details & Skills Demonstrated
Database Platform: MySQL

Design Tool: MySQL Workbench (Used to create the conceptual model, as indicated by the .mwb file).

Database Design: Created a highly normalized schema (multiple tables with defined relationships/foreign keys) to prevent data redundancy and ensure data integrity.

SQL Implementation:

DDL (eSportDBBuild.sql): Scripted the creation of 20+ tables with appropriate data types, primary keys, and Foreign Key constraints (e.g., linking a Player to an Employee and a Team).

DML (eSportDBPopulate.sql): Populated tables with synthetic data covering employees (C-Suite, managers, general staff), departments, sponsors, merchandise, and customers.

Querying (eSportDBTestQueries.sql - not fully shown, but implied): Used to write complex SQL queries to extract meaningful insights (e.g., "Find the total salary cost per department," or "Track which equipment is linked to which sponsorship").

Data Integrity: Demonstrated skill in using constraints (ON DELETE NO ACTION, ON UPDATE NO ACTION) and managing specific relationships (e.g., ensuring a Player/Coach/Content Creator is also tracked as a general Employee).

📈 Business Value
This database acts as the single source of truth for the eSports organization, enabling critical analysis for decision-making in areas like:

Finance: Total salary expenditure, contract tracking (Player, Sponsorship).

HR/Logistics: Employee reporting structure, building/department assignments.

Inventory: Quantity on Hand (QOH) tracking, cost and selling price analysis for merchandise.

Management: Tracking team rosters, league participation, and coach assignments.
