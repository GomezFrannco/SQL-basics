# SQL Basics Data Types

Here is a list of the most common data types used in SQL:

| Data Type    | Description   | Values             |
|--------------|---------------|--------------------|
| Int          | Integer number| 200                |
| Text(n)      | Text          | Abcdef             |
| Varchar(n)   | Alphanumeric  | AB123CD            |
| Date         | Date          | 21/03/1975         |
| DateTime     | Date and time | 21/03/1975 15:00:00|
| Boolean      | True or False | True/False         |
| Decimal(f, s)| Decimal       | 3008,24            |
| Numeric(f, s)| Numeric       | 1407,97            |


---

> * Text(n) and Varchar(n) --> The parameter is a maximum number (integer) of characters that is available to put in the field. 
> * Decimal(f, s) and Numeric(f, s)--> Decimal and Numeric has two parameters. First: Length of the integer; Second: Length of the decimal.

```SQL
-- We only can put an integer with a maximum length of 4 numbers without decimal because the second parameter is 0
Numeric(4, 0); 

-- Exaple: 1552
```