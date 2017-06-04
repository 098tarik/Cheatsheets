# SQL

Each object represents data stored in a row

Each field if a column of that row

A database is considered a part of a table


### Queries

_SELECT_ - Access entries
```
SELECT <fieldnames>
```

_FROM_ - Identifies a table to be searched

```
SELECT <field> FROM <table>
```

### New Data

_CREATE TABLE_ - Generates a table
```
CREATE TABLE <table_name> (column_values)
```

_ALTER TABLE_ - Change data by adding/subtracting columns

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

_UPDATE_ - Identifies a table to be modified
```
UPDATE <tablename>
```

_SET_ - Specifies parameters that need updating
```
UPDATE <table> SET <field> to VALUE
```


### Conditionals

_WHERE_ - Use at the end of a statment followed by a conditional, statement will only operate on something if a conditional is true



