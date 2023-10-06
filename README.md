# SQLquestion33
What is the difference between COALESCE() &amp; ISNULL()? 

COALESCE(): COALESCE function in SQL returns the first non-NULL expression among its arguments. If all the expressions evaluate to null, then the COALESCE function will return null.
Syntax:

SELECT column(s), CAOLESCE(expression_1,....,expression_n)
FROM table_name;
ISNULL(): The ISNULL function has different uses in SQL Server and MySQL. In SQL Server, ISNULL() function is used to replace NULL values.
Syntax:

SELECT column(s), ISNULL(column_name, value_to_replace)
FROM table_name;
