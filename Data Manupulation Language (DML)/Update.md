---The SQL UPDATE 

---The UPDATE statement  modify the records in a table.

---UPDATE Syntax
/*   
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
*/

UPDATE Product SET ProductName = 'Rice', City= 'London'
WHERE CustomerID = 2;