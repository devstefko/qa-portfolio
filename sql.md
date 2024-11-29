USE hogwarts;

SELECT \*  
from characters;

SELECT char\_id, fname, lname, patronus  
FROM characters  
WHERE patronus IS NOT NULL;

SELECT \*  
FROM characters  
WHERE lname LIKE '%e';

SELECT SUM(age)  
FROM characters;

SELECT fname, lname, age  
FROM characters  
ORDER BY age DESC;

SELECT \*  
FROM characters  
WHERE age between 50 and 100;

SELECT DISTINCT age  
FROM characters;

SELECT \*   
FROM characters  
where Faculty='Gryffindor' AND age\>30;

SELECT distinct faculty  
FROM characters  
LIMIT 3;

SELECT \*  
FROM characters  
WHERE fname LIKE 'N\_\_\_\_' OR fname LIKE 'L%';

SELECT AVG(Age)  
FROM characters;

DELETE FROM characters  
WHERE char\_id=11;

SELECT \*  
from characters;

SELECT \*  
FROM characters  
WHERE lname LIKE ('%a%');

SELECT fname as ‘Half-Blood Prince’  
FROM characters  
WHERE char\_id='10';

SELECT \*  
from characters;

SELECT char\_id, patronus  
FROM characters  
WHERE patronus IS NOT NULL  
ORDER BY patronus ASC;

SELECT \*  
FROM characters  
WHERE lname IN ('Crabbe', 'Granger', 'Diggory');

SELECT MIN(age)  
FROM characters;

SELECT fname FROM characters  
UNION  
SELECT book\_name FROM library;

SELECT faculty  
COUNT(char\_id)  
FROM characters  
GROUP BY faculty  
HAVING COUNT(char\_id)\>1;

