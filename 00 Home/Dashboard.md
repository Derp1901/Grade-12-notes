---
type: dashboard
aliases:
  - Home
---
# 🎯 CAET + Boards · Mission Control

> [!important] **CAET Session 1: Sunday, 22 Nov 2026**
> Registration closes **Sat, 14 Nov 2026 at 5:00 PM UAE time**. If registered, ignore that reminder. This plan assumes **CBSE Class 12**; adapt board topics if you're on another syllabus.

[[Start Here]] · [[21-Day Roadmap]] · [[Checklist Hub]] · [[Error Log]] · [[Formula Sheet]] · [[After CAET - Boards Reset]]

## 🚀 Open today's plan

```dataview
TABLE WITHOUT ID file.link AS "Today's note", focus AS "Plan", mode AS "Type"
FROM "02 Daily Plan"
WHERE date = date(today)
```

> [!tip] No row above?
> You're viewing this before or after the scheduled 1–22 November window. Start with [[2026-11-01]], [[2026-11-02]], or open [[21-Day Roadmap]].

## 🗓️ This week's time budget

> [!tip] More time on Mon · Tue · Wed
> **Mon–Wed: 4h20m active** (three subjects). **Thu–Sun: 2h35m typical** (two subjects), apart from your three scheduled full mocks and light Nov 21. Each daily note has its own checklist and a shortened option.

```dataview
TABLE WITHOUT ID file.link AS "Date", capacity AS "Day type", minutes AS "Target minutes", focus AS "Focus"
FROM "02 Daily Plan"
WHERE type = "daily" AND date >= date(today) AND date < date(today) + dur(7 days)
SORT date ASC
```

## ✅ Due / unfinished

```tasks
not done
path includes 02 Daily Plan
due before tomorrow
sort by due
limit 18
```

## 🔭 Next seven days

```tasks
not done
path includes 02 Daily Plan
due after today
due before in 8 days
sort by due
limit 25
```

## 📊 Chapter strength summary · [[Checklist Hub]]

```dataview
TABLE WITHOUT ID key AS "Subject", length(rows) AS "Chapters", length(filter(rows, (r) => r.strength = "Strong")) AS "Strong", length(filter(rows, (r) => r.strength = "Weak")) AS "Weak", length(filter(rows, (r) => r.strength = "Not studied")) AS "Not studied", length(filter(rows, (r) => r.reviewed)) AS "Reviewed"
FROM "03 Chapter Library"
WHERE type = "chapter"
GROUP BY subject
SORT key ASC
```

## 🔥 Weak chapters to prioritize

```dataview
TABLE WITHOUT ID file.link AS "Open chapter", subject AS "Subject", strength AS "Current strength", track AS "Exam"
FROM "03 Chapter Library"
WHERE strength = "Weak" OR strength = "Not studied"
SORT choice(priority = "High", 0, choice(priority = "Medium", 1, 2)) ASC, file.name ASC
LIMIT 20
```

> [!tip] Empty table?
> All chapters are initially **Unrated**. Rate some in [[Checklist Hub]] first. The weak-topic list then fills in automatically.

## 📝 Mock results

```dataview
TABLE WITHOUT ID file.link AS "Mock", completed AS "Finished?", physics AS "Physics", chemistry AS "Chemistry", mathematics AS "Maths", (physics + chemistry + mathematics) AS "Total"
FROM "04 Mocks"
WHERE type = "mock"
SORT date ASC
```

## 🌱 What to do when overwhelmed

1. Open today's note, **only do Focus A**.
2. Practise 5 questions, check answers, and write down the one mistake that matters.
3. If you still have energy, do Focus B. Otherwise stop without trying to cram tomorrow's tasks.

> [!warning] This vault is a flexible study guide, **not an official topic-weightage prediction**. Reprioritize after rating strengths and reviewing mock errors.
