--- OR Operator
---The Where clause can contain one or more or operator to filter sql table.

---SELECT column1, column2, ... FROM table_name WHERE condition1 OR condition2 OR condition3 ...;

---if one condition is true for or operator, sql query will work.

---Example 1
SELECT *FROM Customers WHERE Country = 'Germany' OR Country = 'Spain';

---Example 2 
SELECT * FROM Customers  WHERE City = 'London' OR CustomerName LIKE '%F' OR Country = 'The UK';