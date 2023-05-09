# Some basic SQL tips

Get number of rows in SQL table:

```SQL
SELECT
COUNT(*)
FROM [database].[dbo].[table]
```

Get number of columns in SQL table:

```SQL
SELECT
COUNT(COLUMN_NAME)
FROM INFORMATION_SCHEMA.COLUMNS
WHERE TABLE_CATALOG = 'database'  AND TABLE_SCHEMA = 'dbo' AND TABLE_NAME = 'table'
```
