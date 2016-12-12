# SQL-String-Replace-Helper

## What?
Generate SQL command to replace a string in your database like this:

```javascript
UPDATE [Table]
SET [Column] = REPLACE([Column], '[What to replace]', '[Replace with]')
WHERE [Column] LIKE '%[What to replace]%'
```

## Why?
I wrote it, because i allways stuck with it... ;-)