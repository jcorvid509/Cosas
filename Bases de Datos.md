> **Auditoria** comprobar quien ha realizado que acción

- Auditoria Tradicional
- Auditoria

```sql
SELECT VALUE FROM V$OPTION WHERE PARAMETER = "Unified Auditing"
```

```sql
SHOW PARAMETER AUDIT;
```
