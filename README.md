# Roundtable OS｜圓桌工作系統

Roundtable OS is a project-based collaboration system for AI role teams.

它不是單純的每日會議紀錄，也不是單一 AI Agent 工作流，而是一套讓多個 AI 角色像不同部門一樣，圍繞同一個「痛點 / 功能 / 專案檔」共享脈絡、接力產出、整理決策、交接任務、壓縮文件並長期沉澱的文件系統。

---

## Core idea

> One project file, multiple AI roles, shared context, clear decisions, compact memory.

Roundtable OS is designed for people who want to use multiple ChatGPT conversations, custom roles, or AI assistants as a collaborative team without losing context between rooms.

Instead of organizing discussions by date, Roundtable OS organizes work by **project lifecycle**:

```text
Pain point / idea
↓
Roundtable discussion
↓
Role-specific outputs
↓
Decision
↓
Tasks / handoffs
↓
Compacted summary
↓
Completed / paused / merged / archived
```

---

## Who is this for?

Roundtable OS is useful for:

- Solo founders using AI as a small team
- Creators building content, tools, templates, or products
- Indie makers validating ideas before building
- Small teams that want structured AI-assisted decision-making
- Anyone running multiple AI role chats that need to share context

---

## Repository structure

```text
roundtable-os/
├─ README.md
├─ LICENSE.md
├─ NOTICE.md
├─ TRADEMARKS.md
├─ COMMERCIAL.md
│
├─ 00_system/
│  ├─ current_context.md
│  ├─ role_map.md
│  ├─ operating_rules.md
│  └─ project_status_index.md
│
├─ 01_project_files/
│  ├─ README.md
│  └─ _PROJECT_TEMPLATE/
│     ├─ 00_project_brief.md
│     ├─ 01_roundtable_log.md
│     ├─ 02_role_outputs/
│     ├─ 03_decisions.md
│     ├─ 04_tasks.md
│     ├─ 05_handoffs.md
│     ├─ 06_assets.md
│     ├─ 07_compacted_summary.md
│     ├─ 08_changelog.md
│     └─ 99_raw_archive.md
│
├─ 02_global_records/
│  ├─ decision_log.md
│  ├─ pain_point_index.md
│  ├─ tool_index.md
│  ├─ template_index.md
│  ├─ app_hypothesis_index.md
│  └─ paused_projects.md
│
├─ 03_templates/
│  ├─ project_file_template.md
│  ├─ role_response_template.md
│  ├─ handoff_template.md
│  ├─ decision_template.md
│  └─ slimming_template.md
│
├─ 04_compaction_room/
│  ├─ compaction_rules.md
│  ├─ compaction_queue.md
│  └─ compaction_reports/
│
└─ 99_archive/
```

---

## The 8 default rooms

Roundtable OS starts with 8 generic rooms:

1. **Control Room** — strategy, decisions, prioritization, scope control
2. **Audience Insight Room** — audience, pain points, user research
3. **Shortform Room** — short posts, observations, discussion prompts
4. **Content Room** — structured content, social posts, scripts, CTAs
5. **Free Tool Room** — small tool concepts, input/output design, MVP scope
6. **Template Product Room** — templates, SOPs, paid knowledge products
7. **Product Room** — feature hypotheses, product roadmap, MVP judgment
8. **Compaction Room** — document slimming, context preservation, noise removal

You can rename these rooms for your own project.

---

## How to start

1. Copy `01_project_files/_PROJECT_TEMPLATE/`.
2. Rename it using a project code, for example:

```text
P-001_customer-pain-point
T-001_free-tool-idea
M-001_template-product
A-001_app-feature-hypothesis
```

3. Fill in `00_project_brief.md`.
4. Ask the relevant AI role rooms to respond using `03_templates/role_response_template.md`.
5. Record each response in `01_roundtable_log.md` and the role-specific output file.
6. Let the Control Room decide what becomes official.
7. When files become too long, send them to the Compaction Room.
8. Keep `07_compacted_summary.md` short enough for the next role to continue without rereading everything.

---

## Core rule

> Roles can propose. The Control Room decides. The Compaction Room can shorten, but must not change meaning.

---

## Status labels

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

---

## License and usage

Roundtable OS Core is open under **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You may use, share, adapt, and build upon the documentation, templates, workflows, and written materials, including for commercial use, as long as you provide attribution.

Recommended attribution:

```text
Based on Roundtable OS｜圓桌工作系統 by KL-4ndroid and Roundtable OS contributors, licensed under CC BY 4.0.
```

See:

- `LICENSE.md` for license details
- `NOTICE.md` for attribution guidance
- `TRADEMARKS.md` for name and branding usage
- `COMMERCIAL.md` for commercial offerings and open-core direction

---

## Commercial direction

The core system is open so more people can use, adapt, and improve it.

Premium templates, setup services, workshops, consulting, hosted tools, automation scripts, vertical versions, or official programs may be offered separately.

In short:

> Core open. Brand protected. Advanced implementation can be commercial.
