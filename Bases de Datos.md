> **Auditoria** comprobar quien ha realizado que acción

- Auditoria Tradicional
- Auditoria

```sql
SHOW PARAMETER AUDIT;
```
```sql
SQL> SHOW PARAMETER AUDIT

NAME                         TYPE    VALUE                      

---------------------------- ------- -------------------------- 

audit_file_dest              string  C:\ORACLE\ADMIN\ORCL\ADUMP 

audit_sys_operations         boolean TRUE                       

audit_trail                  string  DB                         

unified_audit_sga_queue_size integer 1048576                    

unified_audit_systemlog      boolean FALSE 
```
