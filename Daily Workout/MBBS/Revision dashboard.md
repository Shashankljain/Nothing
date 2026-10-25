
```dataview id="q2mt9f"
TABLE subject AS "Subject", d1_due AS "Due Date"
FROM "MBBS/Topics"
WHERE type = "topic"
AND d1_done = false
AND date(d1_due) <= date(today)
SORT d1_due ASC
```
