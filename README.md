# storedatabase


CREATE TABLE dodo_store (id INTEGER PRIMARY KEY, article TEXT, price INTEGER, color TEXT, quantity INTEGER);
INSERT INTO dodo_store VALUES (1, "t-shirt", 5.00, "black", 3 );
INSERT INTO dodo_store VALUES (2, "camisol", 7.00, "white", 4 );
INSERT INTO dodo_store VALUES (3, "jupe", 6.00, "green", 7 );
INSERT INTO dodo_store VALUES (4, "nike", 20.00, "purple", 8);
INSERT INTO dodo_store VALUES (5, "sandale", 8.00, "pink", 7 );
INSERT INTO dodo_store VALUES (6, "vernis", 7.00, "red", 4 );
INSERT INTO dodo_store VALUES (7, "ceinture", 15.00, "black", 7 );
INSERT INTO dodo_store VALUES (8, "montre", 25.00, "white", 8);
INSERT INTO dodo_store VALUES (9, "tasse", 7.00, "white", 6 );
INSERT INTO dodo_store VALUES (10, "semele", 11.00, "white", 7 );
INSERT INTO dodo_store VALUES (11, "bague", 10.00 , "gold", 6);
INSERT INTO dodo_store VALUES (12, "pyjama", 9.00, "pink", 3 );
INSERT INTO dodo_store VALUES (13, "mayo", 20.00, "red", 6 );
INSERT INTO dodo_store VALUES (14, "lacet", 3.00, "black", 15 );
INSERT INTO dodo_store VALUES (15, "bretelle", 4.00 , "white", 5);

Select * From dodo_store;

Select * From dodo_store where color = "white";

Select SUM(quantity), SUM(price) From dodo_store;

Select * From dodo_store order by price;

#  this link bring you to my khancacdemy storedatabase created
https://fr.khanacademy.org/computer-programming/projet-driv-de-projet-concevoir-une-base-de-donnes-de-magasin/6175181142278144
