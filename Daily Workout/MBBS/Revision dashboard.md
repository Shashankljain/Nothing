
## 📅 Upcoming Revisions — Next 7 Days

```dataview
TABLE subject AS "Subject",

🔥 Revisions Due Today

TABLE WITHOUT ID

  file.link AS "Topic",

  subject AS "Subject",

  choice(d1_done = false AND d1_due <= date(today), "D+1", "") +

  choice(d3_done = false AND d3_due <= date(today), " D+3", "") +

  choice(d7_done = false AND d7_due <= date(today), " D+7", "") AS "Revision Due"

FROM "MBBS/Topics"

WHERE type = "topic"

AND (

  (d1_done = false AND d1_due <= date(today))

  OR (d3_done = false AND d3_due <= date(today))

  OR (d7_done = false AND d7_due <= date(today))

)

SORT file.name ASC

d1_due AS "D+1 Due",
d3_due AS "D+3 Due",
d7_due AS "D+7 Due"
FROM "MBBS/Topics"
WHERE type = "topic"
AND (
  (d1_done = false AND date(d1_due) > date(today) AND date(d1_due) <= date(today) + dur(7 days))
  OR
  (d3_done = false AND date(d3_due) > date(today) AND date(d3_due) <= date(today) + dur(7 days))
  OR
  (d7_done = false AND date(d7_due) > date(today) AND date(d7_due) <= date(today) + dur(7 days))
)
SORT d1_due ASC
```
