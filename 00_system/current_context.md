# Current Context｜目前圓桌狀態

This file is the shared starting point for every role.

每個 AI 角色在開始回答前，應優先閱讀本文件。它不是完整歷史紀錄，而是目前專案系統的最新狀態摘要。

---

## System name

**Roundtable OS｜圓桌工作系統**

---

## Current system purpose

Roundtable OS is a project-based AI role collaboration system.

Its purpose is to help multiple role-based AI chats work around the same project file, share context, avoid repeated explanations, preserve decisions, and keep long-running discussions usable through compaction.

---

## Current operating model

Roundtable OS uses **project-based files**, not date-based logs.

A project may represent:

- A pain point
- A feature idea
- A free tool
- A content topic
- A template product
- A product hypothesis
- A paused or merged direction

Each project continues until it is completed, paused, merged, retired, or archived.

---

## Current default rooms

1. Control Room
2. Audience Insight Room
3. Shortform Room
4. Content Room
5. Free Tool Room
6. Template Product Room
7. Product Room
8. Compaction Room

---

## Current core rule

> Roles can propose. The Control Room decides. The Compaction Room can shorten, but must not change meaning.

---

## Required role startup guardrail

Every role room must follow:

```text
00_system/role_startup_protocol.md
```

This protocol defines the shared reading order, role boundary check, anti-drift checklist, handoff rules, and Control Room checkpoint.

If a role conversation starts to drift, return to:

1. `00_system/current_context.md`
2. `00_system/role_startup_protocol.md`
3. the target project's `00_project_brief.md`
4. the target project's `07_compacted_summary.md`
5. the target project's `03_decisions.md`
6. Control Room for final decision

---

## Current active projects

| Project ID | Project name | Status | Current next step |
|---|---|---|---|
| P-001 | Instagram 手作市集品牌主痛點探索 | VALIDATING | Send to Audience Insight Room, then Instagram Content Room |

---

## Current next step

Continue `P-001_instagram-pain-point-discovery`:

1. Ask `01｜Audience Insight Room` to refine pain point categories and observation questions.
2. Ask `03｜Instagram Content Room` to turn the 14-day plan into post topics, story prompts, and CTAs.
3. Return to `00｜Control Room` on Day 7 and Day 14 for signal review and decision.

---

## Last updated

2026-07-02