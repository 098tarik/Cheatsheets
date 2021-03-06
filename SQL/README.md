# SQL

Each object represents data stored in a row

Each field if a column of that row

A database is considered a part of a table


### Queries

**SELECT** - Access entries
```
SELECT <fieldnames>
```

**FROM** - Identifies a table to be searched

```
SELECT <field> FROM <table>
```

#### Advanced SELECTS

**DISTINCT** - display each unique field once

**WHERE** - filter elements by requirements, displays only rows that fulfill that boolean expression

**LIKE** - Compare strings to RegEx

**BETWEEN** - Matches items within a range

#### Output Formats
**ORDER BY** - organize items being returned by a column

**LIMIT** - only return a certain number of entries

**GROUP BY** - Group like items together



### New Data

**CREATE TABLE** - Generates a table
```
CREATE TABLE <table_name> (column_values)
```

**ALTER TABLE** - Change data by adding/subtracting columns

Add a column field
```
ALTER TABLE <table_name> ADD <column_name> <data_type>
```

Delete a column
```
ALTER TABLE <table_name> DROP COLUMN <column_name>
```

Modify a column
```
ALTER TABLE <table_name> MODIFY COLUMN <column_name> <data_type>
```

### Changing Table Data

**UPDATE** - Identifies a table to be modified
```
UPDATE <tablename>
```

**SET** - Specifies parameters that need updating
```
UPDATE <table> SET <field> to VALUE
```

### Aggregate Functions
Do math on numeric data types

**COUNT** - count a set of returned items

**SUM** - add a series of items

**AVG** - calculate average value of a set of numbers

**MAX** - return highest value from a set

**MIN** - return lowest value for a set

**ROUND** - Reduce a float to a certain number of decimal spaces
```
ROUND(Val,Significance)
```

### Joins
Join operations combine tables by specifying which fields overlap.
```
SELECT * FROM table_1
JOIN table_2 ON
  table_1.f1 = table_2.f2
```


### Conditionals

**WHERE** - Use at the end of a statment followed by a conditional, statement will only operate on something if a conditional is true



### Data Types

| Data Type | Definition |
| --- | --- |
| NULL | values that are blank (unassigned) |
| Integer | number (signed) |
| Real | decimal |
| Text | a string value |
|  Date | YYY-MM-DD |

### Operators

| Boolean Operators | |
| --- | --- |
| = | equality |
| != | inequality |
| > | greater than |
| < | less than |
| >= | greater than/equal |
| <= | less than/equal |

