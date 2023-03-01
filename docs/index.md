# Module07 Website
---
[Google Homepage](https://www.google.com "Google's Homepage")

[GitHub Webpage Code CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Chris Schnoor

01MAR2023

# Assignment 07
## Introduction
In this assignment, I will discuss the use of SQL user defined functions (UDF) and the differences between scalar inline, and multi-statement functions.
## When to use a SQL User Defined Function (UDF)
User defined functions are used when there is a desire to have results returned that are beyond the standard functions.  By defining the rules of the function, the user can create functions that can be called to return results that can be far more complex than using stock functions.
## Differences between Scalar, Inline, and Multi-Statement Functions
Scalar functions allow for the return of a single value.  A scalar function can be called similar to a view.  An inline function is a tabular function that will contain only one select statement, therefor limiting the complexity of the values returned.  A multi-statement function allows for building of a return table with multiple rows.  Tabular functions must be called similarly to tables by using a FROM clause.
## Conclusion
Functions allow for a convenient grouping of code that can be called repeatedly against a database.  Different UDFs allow for different displays of returned data.  By grouping the code together for reuse, it allows for easy execution against variable inputs.
