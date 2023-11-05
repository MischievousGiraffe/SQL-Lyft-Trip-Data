# SQL-Lyft-Trip-Data
Codecademy SQL Objective Assignment 
Let’s practice what we learned about joins by combining rows from different tables.

Suppose you are a Data Analyst at Lyft, a ride-sharing platform. For a project, you were given three tables:

1) trips: trips information
2) riders: user data
3) cars: autonomous

 ![Lyft Assignment](https://github.com/MischievousGiraffe/SQL-Lyft-Trip-Data/assets/131219174/0c807d00-5de5-4769-8834-e45ec68aa25a)
cars

* What are the column names?
* What’s the primary key of trips?
* What’s the primary key of riders?
* What’s the primary key of cars?
* Try out a simple cross join between riders and cars. Is the result useful?
* Suppose we want to create a Trip Log with the trips and its users. Find the columns to join between trips and riders and combine the two tables using a LEFT JOIN. Let trips be the left table.

  
* Suppose we want to create a link between the trips and the cars used during those trips. Find the columns to join on and combine the trips and cars table using an INNER JOIN.
* The new riders data are in! There are three new users this month. Stack the riders table on top of the new table named riders2.
* What is the average cost for a trip?
* Lyft is looking to do an email campaign for all the irregular users. Find all the riders who have used Lyft less than 500 times!
* Calculate the number of cars that are active.
* It’s safety recall time for cars that have been on the road for a while. Write a query that finds the two cars that have the highest trips_completed.
