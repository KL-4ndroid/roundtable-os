# Operating Rules｜運作規則

This file defines how Roundtable OS should be used.

---

## 1. Project-based, not date-based

Roundtable OS does not organize work primarily by date.

Each major idea, pain point, tool, template, or feature gets its own project folder.

A project folder continues until the project is:

- completed
- paused
- merged
- retired
- archived

Dates can appear inside logs, but dates should not be the main organizing unit.

---

## 2. Source of truth hierarchy

When documents conflict, use this priority order:

1. `00_project_brief.md` inside the project folder
2. `07_compacted_summary.md` inside the project folder
3. `03_decisions.md` inside the project folder
4. `02_global_records/decision_log.md`
5. role-specific output files
6. raw roundtable logs
7. archived raw material

Raw logs preserve history, but they are not the most current source of truth.

---

## 3. Role reading order

Before responding, each role should read:

1. `00_system/current_context.md`
2. the target project's `00_project_brief.md`
3. the target project's `07_compacted_summary.md`
4. the relevant role output file under `02_role_outputs/`
5. the specific task or handoff request

Only read `01_roundtable_log.md` or `99_raw_archive.md` when more detail is needed.

---

## 4. Role writing rules

Each role response should include:

- role name
- task received
- key conclusion
- reasoning
- risks or objections
- suggested next role
- status label

Use `03_templates/role_response_template.md` as the default format.

---

## 5. Status labels

Use these labels consistently:

```text
IDEA       Initial idea
DISCUSSING Roundtable discussion
VALIDATING Validation in progress
BUILDING   Being created
LAUNCHED   Published or released
PAUSED     Paused intentionally
MERGED     Merged into another project
RETIRED    Retired or archived
```

For individual statements, use:

```text
[Observation]
[Assumption]
[Recommendation]
[Decision]
[Risk]
[Objection]
[Pending validation]
[Paused]
[Rejected]
```

---

## 6. Decision authority

Only the Control Room can mark something as an official decision.

Other rooms may recommend, analyze, draft, or object, but they must not treat their own output as final strategy.

Every decision should be recorded in:

- the project-level `03_decisions.md`
- the global `02_global_records/decision_log.md` when it affects the wider system

---

## 7. Compaction authority

The Compaction Room can shorten and reorganize documents, but it must not:

- change a decision
- delete objections
- remove important risks
- convert assumptions into confirmed facts
- erase original user intent
- permanently delete raw context

Raw material should be moved to archive, not destroyed.

---

## 8. When to trigger compaction

Send a file to the Compaction Room when one or more of these conditions are met:

- `01_roundtable_log.md` becomes difficult to scan
- the same point appears more than three times
- a role has to reread too much raw context to continue
- decisions are buried inside long discussion
- the project has reached a new phase
- before handing the project to another role for major work

Suggested practical thresholds:

- more than 500 lines
- more than 30 KB
- more than 5 role-response cycles
- after any major decision

---

## 9. Do not lose minority objections

A minority objection may be more valuable than a repeated agreement.

Compaction must preserve:

- objections
- risks
- reasons for pausing
- unresolved questions
- user constraints
- original user wording when important

---

## 10. Completion rule

A project is not considered complete just because a role has produced content.

A project is complete only when:

1. the Control Room has made a final decision
2. tasks are either done or intentionally paused
3. the project brief is updated
4. the compacted summary is updated
5. any global indexes are updated
6. the changelog records the final update

---

## 11. Minimal viable discipline

Roundtable OS should help reduce confusion, not create more administration.

When in doubt, update only these four files first:

```text
00_project_brief.md
01_roundtable_log.md
03_decisions.md
07_compacted_summary.md
```

Then update the global indexes only when a decision becomes official.
