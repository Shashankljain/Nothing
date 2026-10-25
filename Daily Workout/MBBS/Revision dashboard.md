
```dataview
TABLE subject AS "Subject",
d1_due AS "Stored Due Date",
date(d1_due) AS "Parsed Due Date",
date(today) AS "Today",
d1_done AS "Completed"
FROM "MBBS/Topics"
WHERE type = "topic"
AND d1_done = false
```
