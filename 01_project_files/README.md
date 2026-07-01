# Project Files｜專案檔案區

This folder stores all project-based roundtable files.

Each folder represents one pain point, idea, tool, template, product hypothesis, or system improvement.

---

## Naming convention

Use this format:

```text
<CODE>-<NUMBER>_<short-kebab-or-readable-name>
```

Examples:

```text
P-001_customer-pain-point
C-001_content-series-idea
T-001_free-tool-generator
M-001_template-product
A-001_product-feature-hypothesis
S-001_system-improvement
```

---

## Project type codes

| Code | Meaning |
|---|---|
| P | Pain point |
| C | Content topic |
| T | Free tool |
| M | Template / knowledge product |
| A | App or product feature hypothesis |
| S | System improvement |

---

## How to create a new project

1. Copy `_PROJECT_TEMPLATE/`.
2. Rename the folder with a project code.
3. Fill in `00_project_brief.md`.
4. Add the project to `00_system/project_status_index.md`.
5. Add it to the relevant global index under `02_global_records/`.
6. Start recording role responses in `01_roundtable_log.md`.
7. Keep `07_compacted_summary.md` updated whenever the project becomes too long or changes phase.

---

## Rule

Do not create a new project folder for every small comment.

Create a project folder only when the topic is likely to require multiple role inputs, decisions, validation, or future reuse.
