# sql_odev6
SELECT ROUND(AVG(rental_rate),3) FROM film; --2.980
SELECT COUNT (*) FROM film WHERE title LIKE 'C%'; --92
SELECT MAX(length) FROM film WHERE rental_rate = 0.99; -- 184
SELECT COUNT(DISTINCT replacement_cost) FROM film WHERE length > 150; --21
