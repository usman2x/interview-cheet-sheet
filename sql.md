SQL Essentials

How to improve performance of SQL Queries
	- Proper indexing
	- Transactions
Aggregate data
	- Aggregate functions
		COUNT, AVG, MIN, MAX, SUM

- GROUP BY clause groups the data before calling aggregate functions
- HAVING clause acts as "where" clause of aggregate data, applies after aggregate data
	- filter aggregate data
- WHERE clause operations before the aggregate data
	- filter non aggregate data
- DISTINCT used in aggregate functions, omit duplicates before aggregate applies

- Transactions
	- Group of operations performs in a single unit of work (transaction), if any single operation fails all related
	operations of groups will be rolled back
	- Concurrent operations
	- Increase performance
	- Commit transaction
	- Rollback 
	- Implicit and Explicit Transactions

Indexes
	- Types
		- BTree [Root-> Branch -> Leaf]
		- Primary key, Unique key
	- Improve performance
		- Query applies on specific block rather on entire table
	- Column that are used for filter [where, join] are the best candidate of be indexing
	- Frequent updating tables should have fewer indexes
	- Small tables may not benifit from indexes

Triggers
	- Performed automatically when specific event occurs
	- Actions
		- Before Update, After update, After delete, after insert
	- Used in logging

Views and Subselects
	- View is simple query or join query
	- Views can be indexed but CTE can't
UDF User defined functions
How to select all sessions?

Table partitions
	- Subdivide table into multiple logical and physical tables
	- Horizontal partitioning; means rows are divided not columns
	- Table partitioning key
