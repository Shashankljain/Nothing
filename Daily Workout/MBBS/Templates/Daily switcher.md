
<%*
const parsed = moment(tp.file.title, "YYYY-MM-DD", true);
const d = parsed.isValid() ? parsed : moment();
const date = d.format("YYYY-MM-DD");
const day = d.day();

if (day === 0 || day === 6) {
  tR += `---
type: weekly-review
date: ${date}
---

# 📅 Weekly MBBS Review

## 1. Current Posting

**Posting / subject:**

**Plan today's day**
- [ ] 


**Topics completed:**
- 

**Topics pending:**
- 

- [ ] Review videos completed
- [ ] Review corresponding textbook sections
- [ ] Check understanding of mechanisms
- [ ] Review clinical cases and practical learning
- [ ] Identify unfinished topics



## 2. Parallel Subject

**Subject studied:**

**Topics completed:**
- 

**Topics pending:**
- 


- [ ] Review videos completed
- [ ] Review corresponding textbook sections
- [ ] Check conceptual understanding
- [ ] Review unfinished topics



## 3. Concept Mastery

- [ ] Explain important topics without notes
- [ ] Connect clinical features with pathophysiology
- [ ] Explain investigations and their interpretation
- [ ] Justify management principles
- [ ] Practise relevant clinical cases and viva questions

**Concepts I still find difficult:**
- 

## 4. Revision Dashboard

- [ ] Open the revision dashboard
- [ ] Complete overdue D+1, D+3 and D+7 revisions
- [ ] Identify topics needing further review

## 5. Next Week

**Current posting priorities:**
1.
2.

**Parallel subject priorities:**
1.
2.

**Clinical / practical goal:**

**Main improvement for next week:**
`;
} else {
  tR += `---
type: daily-log
date: ${date}
---

# 📚 Daily MBBS Study Plan

**Date:** ${date}
**College hours:** 9 AM – 4 PM

# A. CURRENT POSTING — PRIMARY TRACK

**Posting / subject:**
**Topic:**
**Plan today's day**
- [ ] 


## 1. Video learning
- [ ] Watch planned lecture
- [ ] Understand the main concepts
- [ ] Record doubts and unclear mechanisms

## 2. Textbook learning
- [ ] Read the corresponding standard textbook section
- [ ] Understand the basic mechanism and pathophysiology
- [ ] Understand clinical features and their rationale
- [ ] Study investigations and interpretation
- [ ] Understand management and its rationale
- [ ] Review complications and differential diagnoses

## 3. Clinical application
- [ ] Connect the topic with current posting
- [ ] Review a relevant case or clinical sign
- [ ] Practise differential diagnosis
- [ ] Review relevant viva / practical questions

**Topic note:** [[MBBS/Topics/]]

**What I understood:**

**What remains confusing:**

---

# B. PARALLEL SUBJECT — MANUAL SELECTION

**Subject:** 
**Topic:**
**Plan today day**
- [ ] 

## 1. Video learning
- [ ] Watch planned lecture
- [ ] Understand the concepts
- [ ] Record doubts

## 2. Textbook learning
- [ ] Read the corresponding standard textbook section
- [ ] Understand mechanisms and principles
- [ ] Connect theory with clinical features
- [ ] Understand investigations and management
- [ ] Clarify anything not explained by the lecture

## 3. Active recall
- [ ] Explain the topic without notes
- [ ] Draw a flowchart or diagram from memory
- [ ] Answer relevant clinical / viva questions

**Topic note:** [[MBBS/Topics/]]

**What I understood:**

**What remains confusing:**

---

# C. REVISION — BOTH SUBJECTS

- [ ] Check D+1 revisions
- [ ] Check D+3 revisions
- [ ] Check D+7 revisions
- [ ] Complete revisions due today
- [ ] Correct previous misconceptions

**Topics revised:**
- 

# D. DAILY REFLECTION

**Best concept understood today:**

**Doubt to clarify:**

**Current posting progress:**

**Parallel subject progress:**

**First task tomorrow:**

## Daily completion
- [ ] Video learning completed as planned
- [ ] Textbook understanding checked
- [ ] Active recall attempted
- [ ] Revision completed as time permits

🔁 Daily Revision Routine

- ☐ Open [[MBBS/Revision Dashboard]]
- ☐ Complete overdue D+1, D+3 and D+7 revisions
- ☐ Use active recall before checking the topic notes
- ☐ Update each revision toggle after completing it
- ☐ Record difficult points in the topic’s Doubts section
`;
}
%>
