
# ORDER BY

SQL'de bir sorgu yürütüldüğünde,
sonuçlanan verileri azalan
veya artan sırada sıralamak için kullanılır.

``` 
SELECT column1, column2, ...
FROM table_name
ORDER BY column1, column2, ... ASC|DESC;
``` 

``` 
SELECT * FROM tableName ORDER BY ColumnName DESC;
SELECT * FROM tableName ORDER BY ColumnName ASC;
``` 
## Sort by Multiple Columns
SQL sorgunuz, "Customers" tablosundaki tüm müşterileri "Country" ve "CustomerName" sütunlarına göre sıralayarak seçer.
Bu, sıralamanın önce Country'ye göre yapıldığı ve bazı satırların aynı Country değerine sahip olması durumunda CustomerName'e göre sıralandığı anlamına gelir.
``` 
SELECT * FROM Customers ORDER BY Country, CustomerName;
``` 
Using ASC and DESC together
SQL sorgusunda, "TableName" tablosundaki tüm müşterileri "ColumnName1" 
---sütununa göre artan, "ColumnName2" sütununa göre ise azalan sırada sıralayarak seçer:

SELECT * FROM TableName ORDER BY ColumnName1 ASC, ColumnName2 DESC;

