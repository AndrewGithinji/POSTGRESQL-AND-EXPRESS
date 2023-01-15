## Creating a Table ##

first_database=# CREATE TABLE table1 (id SERIAL PRIMARY KEY, column1 VARCHAR(255) NOT NULL, column2 INTEGER NOT NULL, column3 DATE, column4 TEXT);
CREATE TABLE
first_database=# CREATE TABLE table2 (id SERIAL PRIMARY KEY, column1 VARCHAR(255) NOT NULL, column2 DATE, column3 INTEGER NOT NULL, column4 TEXT);
CREATE TABLE

// Adding info into first_database //

first_database=# INSERT INTO table1 (column1, column2, column3, column4) VALUES ('Testing out', '2', '2023-01-14', 'Postgre');

// Read the info from first_database //

first_database=# SELECT * FROM table1;

// updating the list //

first_database=# UPDATE table1 SET column2 = 4 WHERE id=1;

// deleting from a Row //

DELETE FROM first_database WHERE id=1;

// LIMIT filter //

SELECT * FROM table1 LIMIT 5;

// BETWEEN selects the values between 2 responses //

SELECT name FROM column1 WHERE column3 BETWEEN '2023-01-01' AND '2023-01-14';

// LIKE identifies content that matches based on patterns //

SELECT name, column4 FROM table1 WHERE name LIKE '%post%';

// checks if a value is or is not NULL // // Used inconjuction with another filter word //

SELECT name, id FROM table1 WHERE column3 IS NULL;

SELECT name, id FROM table1 WHERE column2 IS NOT NULL; 

// returns info on Specified columns //

SELECT name, sighting_date FROM animals WHERE sighting_date BETWEEN '2023-01-01' AND '2023-01-10';

// Return the count Of Specified column //

SELECT COUNT(*) FROM animals WHERE sighting_date BETWEEN '2023-01-01' AND '2023-01-10';

