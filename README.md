# SQL2005 How to reduce logs

```sql
CHECKPOINT
DBCC SHRINKFILE ('[database_name]_LOG', 10)
```
