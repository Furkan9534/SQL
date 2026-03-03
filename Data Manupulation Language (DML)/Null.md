# NULL
Null'ın hiçbir değeri yoktur. Tablonuz null değerler için etkinse,
veriyi null olarak ekleyebilirsiniz.
NULL Değerleri Nasıl Test Edebilirsiniz: Eşittir (=), geometrik (<) veya küçüktür (<>) gibi karşılaştırma operatörleriyle boş (NULL) değerleri test etmek mümkün değildir.
IS NULL ve IS NOT NULL kullanmanız gerekir.

## IS NULL Syntax
```
SELECT column_names
FROM table_name
WHERE column_name IS NULL;
```

```
SELECT column_names
FROM table_name
WHERE column_name IS NOT NULL;
```


-Example 1

SELECT Name, Surname, Phone FROM Customers WHERE Phone IS NULL;

---Example 2

SELECT Name, Surname, Phone FROM Customers WHERE Phone IS NOT NULL;
