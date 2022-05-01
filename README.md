# sql-proje-ödev_1-
SELECT title,description FROM film;  
SELECT*FROM film  WHERE length>60 and length&lt;90; 
SELECT* FROM film  WHERE rental_rate=0.99 and (replacement_cost=12.99 or replacement_cost=28.99);   
SELECT first_name,last_name FROM customer WHERE first_name='Mary'; 
--çıktı : Mary Smith  
SELECT* FROM film  WHERE NOT length>50 and (not rental_rate=2.99 or rental_rate=4.99);
