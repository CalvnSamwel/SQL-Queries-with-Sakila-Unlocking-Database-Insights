# SQL-Queries-with-Sakila-Unlocking-Database-Insights

Project Overview 📑
This project focuses on practicing SQL queries to extract valuable insights from the Sakila database, which contains movie rental information. By performing various SQL operations, you will answer research questions and solve problem statements using fundamental query techniques like SELECT, WHERE, ORDER BY, LIMIT, DISTINCT, and COUNT.
The project also leverages the Entity Relationship Diagram (ERD) of the database to guide analysis, alongside provided SQL files (sakila-schema.sql and sakila-data.sql) to create the database schema and populate it with data, ensuring a complete hands-on learning experience.

Learning Goals 🎯
Upon completion of this project, you will be able to:
- Use SQL queries to extract meaningful insights from structured data.
- Apply techniques such as:- Selecting specific columns with the SELECT clause.
- Filtering data using WHERE conditions.
- Sorting records with the ORDER BY clause.
- Limiting the results using the LIMIT clause.
- Retrieving unique values with DISTINCT.
- Counting records using the COUNT function.



Prerequisites 🛠️
Before beginning this project, you should have a working knowledge of:
- Basic Clauses: SELECT, FROM, WHERE, ORDER BY, and LIMIT.
- Distinct Values: The DISTINCT keyword to retrieve unique records.
- Aliases: Using AS for column aliases.
- Aggregations: The COUNT function to calculate record counts.


Dataset 📊
This project uses the Sakila database, which provides comprehensive details about movie rentals. The data includes tables for actors, films, customers, employees, and more. The following files are essential for database setup:
- Database Schema: sakila-schema.sql to create the structure of the database.
- Sample Data: sakila-data.sql to populate the database tables.
- Entity Relationship Diagram (ERD): Visual representation of the database structure for reference.


Challenges 🧩
You will tackle a series of tasks that require SQL query techniques to analyze the Sakila database:
- Exploration:- Display all tables available in the database.
- Retrieve all records from actor, film, and customer tables.

- Column Retrieval:- Fetch all film titles from the film table.
- List film languages (aliased as language) from the language table.
- Extract first names of employees from the staff table.

- Unique Data Retrieval:- Retrieve distinct film release years.

- Counting Insights:- Count the number of stores owned by the company.
- Determine how many employees are employed.
- Count the total films available for rent and those already rented.
- Find the number of distinct actor last names in the database.

- Film Analysis:- Retrieve the top 10 longest films.

- Filtering Data:- Fetch all actors with the first name "SCARLETT".

- BONUS Queries:- Retrieve movies with "ARMAGEDDON" in their title and a duration greater than 100 minutes.
- Determine the number of films that include Behind the Scenes content.



Requirements ✅
- Fork this repository.
- Clone the repository to your local machine.
- Write SQL queries to solve the challenges listed.


Submission Instructions 📤
- After completing the tasks, save your queries in a .sql file.
- Run the following commands in your terminal:

git add .
git commit -m "Solved lab"
git push origin master


- Submit the repository link via the Student Portal.