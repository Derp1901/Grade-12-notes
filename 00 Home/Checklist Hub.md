---
type: checklist-hub
---
# Chapter checklist · all PCM topics

> [!important] ONE SIMPLE RULE
> **Strength = how well you can solve.** **Revised = you completed practice and checked mistakes.** Don't tick a chapter just because you read it.

## Choose a subject

| | Checklist | What's inside |
|---|---|---|
| ⚡ | [[Physics Checklist\|Physics]] | Electricity, mechanics, waves, modern physics |
| ⚗️ | [[Chemistry Checklist\|Chemistry]] | Physical, inorganic, organic + CAET extras |
| 📐 | [[Mathematics Checklist\|Mathematics]] | Algebra, calculus, vectors, probability |

## Live progress by subject

```dataview
TABLE WITHOUT ID key AS "Subject", length(rows) AS "Total", length(filter(rows, (r) => r.strength != "Unrated")) AS "Rated", length(filter(rows, (r) => r.strength = "Strong")) AS "Strong", length(filter(rows, (r) => r.strength = "Okay")) AS "Okay", length(filter(rows, (r) => r.strength = "Weak" OR r.strength = "Not studied")) AS "Needs work", length(filter(rows, (r) => r.reviewed)) AS "Revised"
FROM "03 Chapter Library"
WHERE type = "chapter"
GROUP BY subject
SORT key
```

## What needs attention first?

```dataview
TABLE WITHOUT ID file.link AS "Open chapter", subject AS "Subject", strength AS "Strength", track AS "Track"
FROM "03 Chapter Library"
WHERE strength = "Weak" OR strength = "Not studied"
SORT choice(priority = "High", 0, choice(priority = "Medium", 1, 2)) ASC, file.name ASC
LIMIT 25
```

> [!tip] Empty focus table?
> Everything starts as **Unrated**, not Weak. Visit a subject checklist and rate just the Class 12 chapters first.

## Quick definitions

- **Not studied** — haven't covered it yet
- **Weak** — need prompts / often wrong
- **Okay** — can solve routine questions, not consistent yet
- **Strong** — fresh timed questions are comfortable
- **Revised** — completed one learning + practice + corrections session (regardless of strength)

[[Dashboard]] · [[21-Day Roadmap]]
