T1 : DROP NULL

Inputs: 
df: SparkDataframe
Columns: List of column names (List[str])
How: All or Any

Example: ........


How : ANY (example): 1 

If any row has at least one column value that is null, we remove that row.

...............

How : ALL (example): 2

If a row has all column values null, we remove only that row.

.................
