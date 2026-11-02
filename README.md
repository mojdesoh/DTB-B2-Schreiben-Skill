# DTB B2 Schreiben Review

An AI skill for grading practice texts for the **Deutsch-Test für den Beruf B2** (DTB B2, also called *telc B2 Beruf*), the exam at the end of the BAMF Berufssprachkurs B2.

It grades the two free-writing tasks:

- **Reply email to a customer** (Lesen und Schreiben, Teil 2), following the Teamleitung's instructions
- **Forumsbeitrag** (Schreiben, item 58), giving an opinion on Thema A or B

## What it checks

| Layer | Source |
|---|---|
| Kriterium I – task completion (email 7 pts, forum post 14 pts) | Official telc criteria |
| II Kommunikative Gestaltung, III Formale Richtigkeit, IV Spektrum (9 pts each) | Official telc criteria |
| At least **4 correctly used B2 grammar points** from a list of 19 | This framework |
| At least **6 B2 vocabulary items**, no overused basic words | This framework |
| Task-specific structure (complaint email, forum post) and plausibility | This framework |

The output covers:
- a score table
- a task checklist
- grammar and vocabulary counts
- a categorised error list
- a minimally corrected version
- two "B2 gut" upgrades
- top 3 priorities
- a one-line progress log

## Folder structure

```
dtb-b2-schreiben-review/
├── SKILL.md   # the skill: instructions, rubric, grammar list, vocabulary lists, output format
└── README.md
```

## Usage

1. Add the `dtb-b2-schreiben-review` folder as a skill in your AI assistant.
2. Submit two things together:
   - **your text**
   - **the task prompt**: the customer email plus the Teamleitung's note, or the full forum topic
3. Repeat over several rounds; the progress line at the end of each review makes it easy to track improvement.

Example message:

> Here is my DTB B2 email. Task: [paste customer email + Teamleitung note]. My answer: [paste text]

## Sources

- telc gGmbH: *Deutsch-Test für den Beruf B2 – Übungstest 1* (2022), sections "Bewertungskriterien Schreiben" and "Punkte und Gewichtung"

## Disclaimer

This is an unofficial practice aid. Scores are estimates. The grammar-point, vocabulary and length rules are study targets, not official telc requirements.
