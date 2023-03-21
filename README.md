# H1 Khan-Academy-Booklist-Project-
Khan Academy is asking me to create a booklist in SQL

[Books I have read and their ratings](https://www.khanacademy.org/computer-programming/spin-off-of-challenge-book-list-database/5808979639058432)

*it is asking me to create a table with a booklist of my favorite books, these are the steps I took to get there*



**STEP ONE creating the table**
CREATE TABLE favoritebooks (
id INTEGER, name TEXT, rating TEXT);

**STEP TWO inserting the values of the books and their ratings**
CREATE TABLE favoritebooks (
id INTEGER, name TEXT, rating TEXT);

INSERT INTO favoritebooks VALUES (1, "Behind Her Eyes", 9.5);
INSERT into favoritebooks VALUES (2, "The Cellar", 6.5);
INSERT into favoritebooks VALUES (3, "City of Fallen Angels", 8);
SELECT * FROM favoritebooks;

**STEP THREE I finished the project on Khan Academy but decided to continue adding books so the link to the list is at the top of this read me**


**Final code looks like this**

CREATE TABLE books (
id INTEGER, name TEXT, rating TEXT);
INSERT INTO books VALUES (1, "Behind Her Eyes", 9.5);
INSERT into books VALUES (2, "The Cellar", 7.5);
INSERT into books VALUES (3, "City of Fallen Angels", 8);
INSERT into books VALUES (4, "Dolores Claiborne", 7.5);
INSERT into books VALUES (5, "The Girl I Used to Be", 7);
INSERT into books VALUES (6, "Girl, Stolen", 6);
INSERT into books VALUES (7, "Verity", 8.5);
INSERT into books VALUES (8, "The Red Scrolls of Magic", 6);
INSERT into books VALUES (9, "Thr Plague Dogs", 7);
INSERT into books VALUES (10, "Blood Will Tell", 4);
INSERT into books VALUES (11, "His", 7);
SELECT * FROM books WHERE rating ORDER BY rating ASC;
