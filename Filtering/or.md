# OR Operator
 WHERE yan tümcesi, SQL tablosunu filtrelemek için bir veya daha fazla "veya" operatörü içerebilir.

```SELECT column1, column2, ... FROM table_name WHERE condition1 OR condition2 OR condition3 ...;```

Eğer "veya" operatörü için bir koşul doğruysa, SQL sorgusu çalışacaktır.

Örnek 1
```SELECT *FROM Customers WHERE Country = 'Germany' OR Country = 'Spain';```

eX 2 
```SELECT * FROM Customers  WHERE City = 'London' OR CustomerName LIKE '%F' OR Country = 'The UK';```