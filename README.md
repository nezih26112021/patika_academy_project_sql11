# patika_academy_project_sql11
query scenarios

Perform the following query scenarios on the "dvdrental" sample database:

1. Let's sort all the data for the "first_name" columns in the actor and customer tables:

(SELECT first_name FROM actor)

UNION

(SELECT first_name FROM customer);

2. Let's sort the intersecting data for the "first_name" columns in the actor and customer tables:

(SELECT first_name FROM actor)

INTERSECT

(SELECT first_name FROM customer);

3. For the "first_name" columns in the actor and customer tables, let's sort the data in the first table but not in the second table:

(SELECT first_name FROM actor)

EXCEPT

(SELECT first_name FROM customer);

4. Let's also do the first 3 queries for repeating data:

4.1.

(SELECT first_name FROM actor)

UNION ALL

(SELECT first_name FROM customer);

4.2.

(SELECT first_name FROM actor)

INTERSECT ALL

(SELECT first_name FROM customer);

4.3.
(SELECT first_name FROM actor)

EXCEPT ALL

(SELECT first_name FROM customer);



