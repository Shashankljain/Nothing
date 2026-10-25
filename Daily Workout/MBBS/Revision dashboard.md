📚 MBBS Revision Dashboard

🔥 D+1 Revisions

TABLE file.link AS "Topic", subject AS "Subject", d1_due AS "Due Date"

FROM "MBBS/Topics"

WHERE type = "topic" AND d1_done = false AND date(d1_due) <= date(today)

SORT d1_due ASC

🔥 D+3 Revisions

TABLE file.link AS "Topic", subject AS "Subject", d3_due AS "Due Date"

FROM "MBBS/Topics"

WHERE type = "topic" AND d3_done = false AND date(d3_due) <= date(today)

SORT d3_due ASC

🔥 D+7 Revisions

TABLE file.link AS "Topic", subject AS "Subject", d7_due AS "Due Date"

FROM "MBBS/Topics"

WHERE type = "topic" AND d7_done = false AND date(d7_due) <= date(today)

SORT d7_due ASC

📅 Upcoming Revisions — Next 7 Days

TABLE file.link AS "Topic", subject AS "Subject",

d1_due AS "D+1 Due", d3_due AS "D+3 Due", d7_due AS "D+7 Due"

FROM "MBBS/Topics"

WHERE type = "topic"

AND (

  (d1_done = false AND date(d1_due) > date(today) AND date(d1_due) <= date(today) + dur(7 days))

  OR (d3_done = false AND date(d3_due) > date(today) AND date(d3_due) <= date(today) + dur(7 days))

  OR (d7_done = false AND date(d7_due) > date(today) AND date(d7_due) <= date(today) + dur(7 days))

)

SORT d1_due ASC

📚 All Topics

TABLE file.link AS "Topic", subject AS "Subject",

posting AS "Posting", date_studied AS "Date Studied"

FROM "MBBS/Topics"

WHERE type = "topic"

SORT date_studied DESC

🎯 All Pending Revisions — Combined List

TABLE WITHOUT ID

  file.link AS "Topic",

  subject AS "Subject",

  choice(d1_done = false AND date(d1_due) <= date(today), "D+1 ", "") +

  choice(d3_done = false AND date(d3_due) <= date(today), "D+3 ", "") +

  choice(d7_done = false AND date(d7_due) <= date(today), "D+7", "") AS "Pending"

FROM "MBBS/Topics"

WHERE type = "topic"

AND (

  (d1_done = false AND date(d1_due) <= date(today))

  OR (d3_done = false AND date(d3_due) <= date(today))

  OR (d7_done = false AND date(d7_due) <= date(today))

)

SORT file.name ASC