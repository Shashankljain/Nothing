🔥 Revisions Due Today

TABLE WITHOUT ID

  file.link AS "Topic",

  subject AS "Subject",

  choice(d1_done = false AND date(d1_due) <= date(today), "D+1 ", "") +

  choice(d3_done = false AND date(d3_due) <= date(today), "D+3 ", "") +

  choice(d7_done = false AND date(d7_due) <= date(today), "D+7", "") AS "Revision Due"

FROM "MBBS/Topics"

WHERE type = "topic"

AND (

  (d1_done = false AND date(d1_due) <= date(today))

  OR (d3_done = false AND date(d3_due) <= date(today))

  OR (d7_done = false AND date(d7_due) <= date(today))

)

SORT file.name ASC