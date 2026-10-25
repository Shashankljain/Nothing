
# 📊 MBBS Subject Progress Dashboard

## 📚 Topics Studied by Subject

```dataview
TABLE
  length(rows) AS "Topics Created",
  length(filter(rows, (r) => r.d1_done = true AND r.d3_done = true AND r.d7_done = true)) AS "Fully Revised"
FROM "MBBS/Topics"
WHERE type = "topic"
GROUP BY subject
SORT length(rows) DESC
```

## 🩺 All Subjects and Topics

```dataview
TABLE subject AS "Subject", posting AS "Posting",
date_studied AS "Date Studied",
d1_done AS "D+1", d3_done AS "D+3", d7_done AS "D+7"
FROM "MBBS/Topics"
WHERE type = "topic"
SORT subject ASC
```
