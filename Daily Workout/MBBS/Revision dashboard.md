
```dataview id="d1final"
TABLE subject AS "Subject", d1_due AS "Due Date", d1_done AS "Completed"
FROM "MBBS/Topics"
WHERE type = "topic"
AND d1_done = false
AND d1_due <= date(today)
SORT d1_due ASC
```
