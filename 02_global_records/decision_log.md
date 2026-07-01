# Global Decision Log｜全域決策紀錄

This file records decisions that affect the whole Roundtable OS workspace.

Project-specific decisions should also live inside each project's `03_decisions.md`.

---

## Decision format

```md
## D-000｜Decision title

【Date】
YYYY-MM-DD

【Decision】
What was decided?

【Why this decision was made】
1.
2.
3.

【Supporting reasons】
1.
2.
3.

【Objections / risks】
1.
2.
3.

【Paused or rejected options】
1.
2.
3.

【Affected files or projects】
- 

【Next actions】
1.
2.
3.

【Owner room】
Control Room

【Review timing】

【Status】
Valid / Pending review / Adjusted / Cancelled
```

---

## Initial system decisions

## D-001｜Use project-based files instead of date-based files

【Date】
2026-07-01

【Decision】
Roundtable OS organizes work by project folders instead of daily files.

【Why this decision was made】
1. A date-based log becomes a timeline, but not a reusable project asset.
2. A pain point, tool, template, or feature may need discussion across many days.
3. Project-based folders preserve the full lifecycle from idea to completion, pause, merge, or archive.

【Supporting reasons】
1. Easier for roles to continue work around one topic.
2. Easier to compact and summarize context by project.
3. Easier to track decisions and tasks.

【Objections / risks】
1. Requires discipline when deciding whether a topic deserves a project folder.
2. Small comments should not create unnecessary projects.

【Paused or rejected options】
- Daily-only file naming as the primary structure.

【Affected files or projects】
- `01_project_files/`
- `00_system/project_status_index.md`

【Next actions】
Use `_PROJECT_TEMPLATE/` for new project folders.

【Owner room】
Control Room

【Status】
Valid

---

## D-002｜Create a Compaction Room

【Date】
2026-07-01

【Decision】
Roundtable OS includes a dedicated Compaction Room for document slimming and context preservation.

【Why this decision was made】
1. Long-running AI role discussions become bloated over time.
2. Important decisions can get buried in repeated or low-value content.
3. Future roles need a short and reliable current summary.

【Supporting reasons】
1. Compaction reduces reading load.
2. Raw logs remain archived for traceability.
3. Preserved objections and risks prevent distortion.

【Objections / risks】
1. Poor compaction may distort meaning.
2. Over-aggressive trimming may delete useful context.

【Paused or rejected options】
- Letting every role summarize however they want without common rules.

【Affected files or projects】
- `04_compaction_room/`
- all project-level `07_compacted_summary.md`

【Next actions】
Use `04_compaction_room/compaction_rules.md` and `03_templates/slimming_template.md`.

【Owner room】
Control Room + Compaction Room

【Status】
Valid
