# SQL随机选择N条数据,SQL随机查询数据
## MYSQL
```sql

SELECT `sp_id`,`sp_name`,`sp_model` FROM `sp` where `sp_type`=1 and `com_net`=0 order by rand() limit 20  
```
## MSSQL
```sql
select top 10 * from oblog_user order by newid() 
```



