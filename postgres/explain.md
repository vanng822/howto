### Find slow queries

https://wiki.postgresql.org/wiki/Logging_Difficult_Queries

Specify this log_min_duration_statement setting in milliseconds to log all queries that are slower than this value

### Sequential Scan

No index reading, scan for all rows. Suitable for small tables or table that need to load all rows often.

### Index Scan  
Need when reading small part of rows. Returning rows in sorted order, good with LIMIT
Scan in index one row then read the row from table ...

### Index Only Scan
Only scan the index, have enough data to return and no need of reading table 

### Bitmap Index Scan
Scan all rows in index and then read from tables
