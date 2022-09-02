# SQL
SQL Portfolio
I created at table to show the items, price, inventory numbers and color of clothes. Which I then had it ordered by price and then showed the total sum of inventory.


CREATE TABLE store (id INTEGER PRIMARY KEY, name TEXT, price INTEGER, quantity INTEGER, color TEXT);

INSERT INTO store VALUES(1, "tshirt", 10, 14, "blue"),
(2, "long_sleeve", 4, 11, "pink"),
(3, "jeans", 10, 14, "Blue"),
(4, "shorts", 5, 12, "dark_blue"),
(5, "bra", 11, 9, "black"),
(6, "panties", 7, 8, "tan"),
(7, "socks", 2, 20, "white"),
(8, "tank_top", 4, 25, "green"),
(9, "jean_shorts", 8, 4, "blue"),
(10, "jacket", 12, 18, "purple"),
(11, "hoodie", 12, 13, "grey"),
(12, "leggings", 6, 30, "black"),
(13, "sandles", 18, 15, "yellow"),
(14, "heels", 22, 15, "orange"),
(15, "shoes", 21, 15, "violet")
;

SELECT * FROM store;
SELECT * FROM store ORDER BY price;
SELECT SUM(price) FROM store;
