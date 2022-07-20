# SQL Databases (Introduction)

**Concept:** When we talk about **relational** databases or **SQL** databases, we said that they are based on a relational model that uses tables to represent data.
If a database has only one table, then it is a flat SQL database.

In the relational model the information is stored on the database in a set of tables, as well as represents the data or the relationships between them.

## TABLES

The table is an object of the database that represents how the data is stored.

**Elements in a table:**

| y| schema|or | header |
|--|-------|---|--------|
| y|       |   |        |
| y|       |   |        |
| x|xxxxxxx|xxx|xxxxxxxx|
| y|       |   |        |
| y|       |   |**FFFF**|
| y|       |   |        |

* In the **schema** or **header** we put the name of the column.
* The **Y** represents a Column in a table 
* The **X** is a Row in the table
* The **F** is a singular field in this table.

## SQL RELATIONS

There are 3 different types of relations in the database.

* One-to-one.
* One-to-many.
* Many-to-many.

---
### One to One.
Any field in any table only appears once and has only one unique relation with another table.

### One to Many.
A field in a table can have relation with many elements in another table.

### Many to Many.
One or more fields can have relation with one or many elements in another table

For this relations we use **KEYS**

---
## TABLE KEYS
