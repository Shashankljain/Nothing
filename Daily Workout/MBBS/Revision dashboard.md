
# 🧠 MBBS Revision Dashboard

## 🔴 D+1 — First Revision

```dataview
TABLE subject AS "Subject", d1_due AS "Due Date"
FROM "MBBS/Topics"
WHERE type = "topic"
AND d1_done = false
AND d1_due <= date(today)
SORT d1_due ASC
```

## 🟠 D+3 — Second Revision

```dataview
TABLE subject AS "Subject", d3_due AS "Due Date"
FROM "MBBS/Topics"
WHERE type = "topic"
AND d3_done = false
AND d3_due <= date(today)
SORT d3_due ASC
```

## 🔵 D+7 — Third Revision

```dataview
TABLE subject AS "Subject", d7_due AS "Due Date"
FROM "MBBS/Topics"
WHERE type = "topic"
AND d7_done = false
AND d7_due <= date(today)
SORT d7_due ASC
```

## 📚 All Topics

```dataview
TABLE subject AS "Subject", posting AS "Posting",
date_studied AS "Date Studied"
FROM "MBBS/Topics"
WHERE type = "topic"
SORT date_studied DESC
```
