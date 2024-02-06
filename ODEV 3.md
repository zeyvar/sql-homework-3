# sql-homework-3
--like, ilike, not like 
--SORU 1
SELECT * FROM country
where country LIKE 'A%a';


--SORU 2
  SELECT * FROM country
 where country ILIKE '____%n' 

-- SORU 3
  SELECT * FROM film
 where title  ILIKE '%T%t%t%t%'

-- SORU 4
 SELECT * FROM film
 where title LIKE 'C%' AND length>90 AND rental_rate=2.99
