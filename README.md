# SQL
SQL Portfolio
Hello There! Welcome to my SQL Portfolio, where I have some examples of SQL's I have written. Please feel free to take a glance and reach out to me if you have any questions at my email ~ mauradarazio00@gmail.com 

STORE TABLE DATABASE:
CREATE TABLE Store (id INTEGER PRIMARY KEY, name TEXT, price INTEGER, aisle INTEGER, quantity INTEGER);
INSERT INTO Store VALUES (1,"boots",30.00,24,5);
INSERT INTO Store VALUES (2,"hats",24.00,12,3);
INSERT INTO Store VALUES (3,"earrings",12.00,4,4);
INSERT INTO Store VALUES (4,"socks",16.00,11,3);
INSERT INTO Store VAlUES (5,"Scarfs",6.00,12,6);
INSERT INTO Store VAlUES (6,"Dresses",25.00,10,10);
INSERT INTO Store VAlUES (7,"shirts",14.00,10,9);
INSERT INTO Store VAlUES (8,"Jeans",40.00,13,15);
INSERT INTO Store VAlUES (9,"Leggings",20.00,13,12);
INSERT INTO Store VAlUES (10,"Skirts",25.00,13,6);
INSERT INTO Store VAlUES (11,"Sweatshirt",35.00,10,8);
INSERT INTO Store VAlUES (12,"Sandals",16.00,24,6);
INSERT INTO Store VAlUES (13,"tennis shoes",26.00,24,9);
INSERT INTO Store VAlUES (14,"sweatpants",26.00,22,7);
INSERT INTO Store VAlUES (15,"sweaters",24.00,24,5);

SELECT * FROM Store WHERE price > 20 ORDER BY quantity;

SELECT * FROM Store WHERE price > 22 ORDER BY id asc;

