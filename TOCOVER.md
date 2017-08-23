# Topics to Cover

This is a list of topics that will be covered in today's lecture.

## What is a relational database? 

## Schemas 
product name of product. primary key is a unique identifier. can be a number.
<!-- CREATE TABLE [tablenameyourusing] (
    [columnname][datatype][constraintsisoptionalbutnotneeded.],

); -->

CREATE TABLE products(
    id SERIAL PRIMARY KEY,
    name TEXT,
    price FLOAT,
);

## Datatypes
-Numeric Types
    -FLOAT - can have up to 15 places after decimal point
    -INTEGER - good for if not worried about super precise data. Rounds numbers.
    -DECIMAL - good for precise numbers.
-Character Types
    -TEXT unlimited character length.
    -VARCHAR(n) n represetns a number. varchar stands for variable character. Character length is limited.
        -VARCHAR(100)
        -two single quotes for a quote in string.


## SQL statement 
-ANything where text starts and ends with a semicolon.
-Also known as query ends w/semicolon. Can create multiple tables at the same time and multiple queries. NEver forget semicolon.
-DISTINCT just removes duplicates.
## SELECTS

## Adding, Updating, Removing Rows in a Table
ORDER BY DESC easier to read or ASC even though default is ascending.
INSERT INTO [tablename]
([column name][...column name])
VALUES
([value], [....value]);

always use a condition when updating stuff