# SQL Functions
KSanchez, 12.3.2020

## Introduction
This week, I learned about the different types of SQL functions, including how to create and use them for reporting. 
I now have a better understanding of the following concepts:

### When to Use a SQL UDF
SQL UDFs or User Defined Functions are custom functions that take parameters. 
UDFs are useful for when a query will be performed multiple times and return a single value and when you can’t find a function that meets your needs. 
They can be used instead of or in addition to SQL Server’s built-in functions, but can affect query performance.

### Similarities and Differences Between Scalar, Inline, and Multi-Statement Functions
Scalar functions allow you to return a single value including a string of text, a number, or a date. 
Simple (In-line) functions return a table of data or single set of rows. The output of in-line functions can be used like any other SQL table or view. 
When selecting functions, both scalar and in-line functions require the dbo prefix (the schema name) for them to work. 
A multi-statement function is a function that returns a table of data, but only after some additional processing. 
Multi-statement functions can also have multiple parameters, but need a table to be defined and typically require rows to be inserted into the table.

## Summary
I now have a better understanding of functions and their uses. 
I can take this knowledge and build upon it to become more comfortable with the different types and determining when they would be most useful.
