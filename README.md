# H1 Khan-Academy-Booklist-Project-
Khan Academy is asking me to create a booklist in SQL

*it is asking me to create a table with a booklist of my favorite books, these are the steps I took to get there*

**STEP ONE creating the table**
CREATE TABLE favoritebooks (
id INTEGER, name TEXT, rating TEXT);



**STEP TWO inserting the values of the books and their ratings**
INSERT INTO favoritebooks VALUES (1, "Behind Her Eyes", 9);
INSERT into favoritebooks VALUES (2, "The Cellar", 7);
INSERT into favoritebooks VALUES (3, "City of Fallen Angels", 8);
SELECT * FROM favoritebooks;
