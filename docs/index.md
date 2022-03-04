# User Defined Functions

## Introduction
This paper will be explaining the purpose of a SQL UDF and differences between Scalar, Inline, and Multi-Statement Functions used in SQL Server.

## Topics

1.	Explain when you would use a SQL UDF.
SQL Server user-defined functions are routines that accept parameters, perform an action, such as a complex calculation, and return the result of that action as a value. The return value can either be a single scalar value or a result set. UDFs can be used to create a function once, store it in the database, and call it any number of times in your program. It also allows faster execution.

2.	Explain are the differences between Scalar, Inline, and Multi-Statement Functions.
-	User-defined scalar functions are used to return a single (scalar) value as an expression. Unlike parameters in table functions, parameters in scalar functions are very useful.
-	For an inline scalar function, the returned scalar value is the result of a single statement.	
-	For a multi-statement scalar function, the function body can contain a series of Transact-SQL statements that return the single value.


## Summary
 In conclusion the  SQL UDFs used in SQL are of foremost importance in order to update, manipulate and maintain the data in a database, or retrieve data from a database.
![image](https://user-images.githubusercontent.com/98923915/156708166-d50c7eaa-3c37-433a-8d7e-f6bd8f14b713.png)
