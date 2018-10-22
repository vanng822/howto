## Schema by name
```sql
select nspname from pg_catalog.pg_namespace where nspname like 'sometab%';
```

## Find tables which have column by name
```sql
select * from INFORMATION_SCHEMA.COLUMNS where COLUMN_NAME like '%my_column%' order by TABLE_NAME
```

## Find function definition by name

```sql
select pg_get_functiondef(oid) from pg_proc where proname = 'my_awsume_func';
```


## Find constraints
```sql
SELECT CONSTRAINT_NAME, table_name FROM information_schema.table_constraints
    WHERE table_schema='public' 
    and constraint_type='FOREIGN KEY'
    and constraint_name like '%my_constrain_key%';
```
