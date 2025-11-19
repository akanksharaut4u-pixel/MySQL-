# MySQL-
ODI Cricket Data Analysis using MySQL

This project demonstrates end-to-end data handling, cleaning, transformation, and analysis of ODI (One Day International) cricket data using MySQL. It includes database creation, dataset import, data preprocessing, SQL classification using CASE statements, and advanced querying for insights.

📂 Project Features
1️⃣ Database & Table Setup

Creates a dedicated database retail_DB2.

Defines table odi_cricket_data2 with 17 player-related attributes including runs, wickets, strike rate, matches, awards, etc.

2️⃣ CSV Data Import

Uses MySQL LOAD DATA INFILE to import ODI cricket statistics from a CSV file into the database.

3️⃣ Data Cleaning & Preprocessing

Fixes inconsistent decimal precision in strike_rate and average.

Removes invalid or negative values.

Updates all-rounder classification.

Deletes players with zero match wins or low match count.

4️⃣ Player Categorization (CASE Statements)

The project includes multiple classification queries such as:

Player Category → Batter / Bowler / All-rounder

Player Class → Legend / Great Player / Average Player / Newcomer

Bowling Category → Elite / Experienced / Developing / Part-Time

Match Impact → Match Winner / Consistent Performer / Contributor

Awards Category → Superstar / Key Player / Occasional Star / Rare Winner

5️⃣ Analytical Queries

Includes top-X analysis for:

Top 10 run scorers (batters)

Top wicket takers (bowlers)

Updates to player stats (e.g., adding runs, modifying strike rate)

Insert/Delete operations for player records

🛠️ Technologies Used

MySQL Server 8.0

SQL (DDL, DML, Data Cleaning, CASE statements)

CSV Data Handling

🗂️ Files Included

AkankshaRautproject1.sql → Complete SQL workflow for database creation, data loading, cleaning & analysis.

ODI_data.csv → Dataset containing detailed ODI cricket player statistics.

🎯 Purpose of the Project

This project is ideal for:

Learning SQL data manipulation and analysis

Practicing advanced SQL queries

Sports analytics & cricket data exploration

Academic SQL assignments (B.Sc./Computer Science)
