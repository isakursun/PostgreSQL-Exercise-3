1. SELECT country FROM country
   WHERE country LIKE 'A%a';

   ![](./images/1.png)

2. SELECT country FROM country
   WHERE country LIKE '_ _ _ _ _%n';

   ![](./images/2.png)

3. SELECT title FROM film
   WHERE title ILIKE '%T%T%T%T%'

   ![](./images/3.png)

4. SELECT \* FROM film
   WHERE (title LIKE 'C%') AND (length > 90) AND (rental_rate IN (2.99));

   ![](./images/4.png)
