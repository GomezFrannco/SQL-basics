# SQL (Structured Query Language)

SQL is a language that allows the user to create specific queries and get a result with this.
The language have its own and particular structure for the queries.

## FIRST LINE OF CODE:

In the following example we are going to write our first SQL sentence.
To write a SQL sentence we need a clause, a value and a semicolon.

```SQL
SELECT random_value;
```

In the previous example, the **SELECT** clause is a **SQL clause** or a keyword that the language provides us.

## COMMENTS

In this example we will write a comment. A comment is a **block of text or code** that will not be executed or read by the SQL language engine.

```SQL
-- This is a comment and this never will be executed.

/*
* betwen this symbols we can write comments.
* SELECT something.
* this never will be executed too.
*/
```
## BASIC QUERY

Here is the first and the most common query that we write when we are learning SQL.

```SQL
SELECT some_column FROM some_table;

-- SELECT and FROM are the SQL keywords.
-- SELECT is following by the name of the column.
-- FROM is following by the name of some table that we want the data comes from
```

## BASIC CONDITION

Conditions is a common feature in programming languages. In SQL we have conditions too, one of them is WHERE:

```SQL
-- WHERE indicates conditions for the query
SELECT some_column FROM some_table WHERE conditions;

-- Example:
SELECT * FROM COMMENTARY WHERE id_system_user = 943;

-- the output of the query will be all the columns and their information or data but only the rows where id_system_user is equal to 943.
```

## COMPARISON OPERATORS

The **comparison operators** are very useful to apply specific conditions or filtering stored data to get an accurate results.

Below is a table of some comparison operators you can use:

| Operator | Description         |
|----------|---------------------|
| =        | Equal to            |
| <        | Less than           |
| >        | Greater than        |
| <=       | Less or Equal to    |
| =>       | Greater or Equal to |
| != or <> | Other than          |
| NOT      | Logical NOT         |
| LIKE     | Logical LIKE        |
| AND      | Logical AND         |
| BETWEEN  | Logical BETWEEN     |
| IN       | Logical IN          |
| OR       | Logical OR          |

---

* **NOTE:** Every time you are going to use comparison operators, the query must have the SQL **WHERE** clause. 

```SQL
SELECT * FROM SUGGEST WHERE id_game BETWEEN 44 AND 46 ;

-- The result of this query should be a value between 44 and 46.
```