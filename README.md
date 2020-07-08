# sql-1-mini

1-SELECT all the data FROM the artist table.

SELECT * FROM artist;

2-SELECT the first_name, last_name, and country FROM the employee table.

SELECT first_name, last_name, country
FROM employee;

3-SELECT the name, composer, and milliseconds FROM the track table WHERE the milliseconds are greater than 299000.

SELECT name, composer, milliseconds
FROM track
WHERE milliseconds > 299000;


4-SELECT the count FROM the track table WHERE the milliseconds are greater than 299000.

SELECT count(*)
FROM track
WHERE milliseconds > 299000;


Find the average length of all tracks in milliseconds
Find the number of invoices in the USA
Make a list of all the First Names of Customers that contain an 'a'
Make a list of the 10 longest tracks
Make a list of the 20 shortest tracks
Find all the customers that live in California or Washington
Find all the customers that live in California, Washington, Utah, Florida, or Arizona (Use IN keyword)
Insert an artist to the database
Insert yourself as a customer to the database
Find a list of all Playlists that start with Classical
