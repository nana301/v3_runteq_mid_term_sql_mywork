## emp_noが40000の従業員の1996年~1997年にかけての給料を教えてください。

### 答え
65185

### SQL
```sql
SELECT salary, from_date, to_date
FROM salaries
WHERE emp_no = 40000
  AND from_date >= '1996-01-01'
  AND to_date <= '1997-12-31';
```
