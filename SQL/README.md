
# Project 1: Population Analysis Using SQL


## Project Overview

In this project, I used SQL queries in MySQL Workbench to explore and analyse the World database. The database contains information about countries, cities, and languages, including population, life expectancy, and GDP. I retrieved, filtered, sorted, grouped, and analysed the data to answer a range of demographic and geographical questions and gain meaningful insights from the dataset.
<br>



### Q1 Count Cities in the USA
<br>
I wrote a SQL query to count the total number of cities in the United States. I used the COUNT(*) function to count all records where the CountryCode is 'USA' and assigned the result the alias Cities_in_USA.
<br>
<br>
<img width="1450" height="530" alt="01-count-cities-usa" src="https://github.com/user-attachments/assets/5c3aef83-0c12-4fea-84f5-63d5b29dffc5" />
<br>
<br>
The query returned 274, showing that there are 274 cities in the World database with the country code USA.
<br>
<br>

### Q2.Country with the Highest Life Expectancy
<br>
I wrote a SQL query to retrieve the country with the highest life expectancy. I selected the Name and LifeExpectancy columns, sorted the results in descending order using ORDER BY, and used LIMIT 1 to return only the highest result.
<br>
<br>

<img width="767" height="655" alt="02-highest-life-expectancy" src="https://github.com/user-attachments/assets/61874e87-cf32-43fd-b9df-b77f3207d5fd" />
<br>
<br>
The query showed that Andorra has the highest life expectancy in the dataset, with a life expectancy of 83.5 years.
<br>

### Q3 Cities Containing "New"

<br>
I wrote a SQL query to search for city names containing the word "New". I used the LIKE operator with the wildcard % to find all cities whose names include "New".
<br>
<br>
<img width="1449" height="1056" alt="03-cities-with-new" src="https://github.com/user-attachments/assets/3bdfc780-edd8-4e81-b640-ee1213f6885b" />
<br>
<br>
The query returned all cities containing "New" in their names, such as New Delhi, New York, New Orleans, Newcastle, and New Haven. This demonstrated how the LIKE operator can be used to search for partial text matches in a database.
<br>
<br>

### Q4 Top 10 Most Populated Cities
<br>
I wrote a SQL query to retrieve the top 10 most populated cities from the city table. I selected the Name and Population columns, sorted the results in descending order using ORDER BY Population DESC, and used LIMIT 10 to display only the ten largest cities.
<br>
<br>

<img width="865" height="1270" alt="04-first-10-rows" src="https://github.com/user-attachments/assets/e7a70e79-3128-42e0-bf8d-5471d4fcff9a" />
<br>
<br>

The query returned the top 10 cities with the highest populations, including Mumbai (Bombay), Seoul, São Paulo, Shanghai, and New York, allowing for an easy comparison of the largest cities in the dataset.

<br>




---

# Project 2: World Database ERD



In this project, I designed an Entity Relationship Diagram (ERD) in MySQL Workbench to understand how the tables are connected. I identified the primary and foreign keys, modelled one-to-many relationships, and reviewed the ERD to ensure the relationships were accurate.



<p align="center">
  <img src="https://github.com/user-attachments/assets/0eb35696-5855-4b60-8e00-7995c460bb93" alt="World Database ERD" width="1000">
</p>



The completed ERD provides a clear visual representation of the relationships between the tables in the World database. It shows how primary and foreign keys connect the tables and demonstrates the one-to-many relationships, making it easier to understand the database structure before writing SQL queries.
<br>
<br>
📄 [View SQL Queries](https://github.com/TigistAbate/TigistA-Data/blob/main/SQL/SQL_Queries.sql)


## Skills Demonstrated

- SQL querying
- Data filtering and sorting
- Aggregate functions (`COUNT`, `AVG`)
- `GROUP BY`
- `ORDER BY`
- `WHERE`
- `LIMIT`
- Data analysis
- Relational database querying and modelling
- MySQL Workbench
- Database design
- Entity Relationship Diagrams (ERDs)
- Primary keys
- Foreign keys
- One-to-many relationships
- Data modelling
