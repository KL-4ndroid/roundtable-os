# Compaction Queue｜文件減肥佇列

Use this file to track files that need compaction.

---

## Queue

| ID | Project | File to compact | Reason | Requested by | Priority | Status | Notes |
|---|---|---|---|---|---|---|---|
| CQ-001 |  |  | Too long / Repeated / Decision buried / Handoff unclear |  | P0 / P1 / P2 | Waiting / Doing / Done / Cancelled |  |

---

## Priority guide

| Priority | Meaning |
|---|---|
| P0 | Blocking role continuation or decision-making |
| P1 | Making the project hard to read, but not blocking |
| P2 | Useful cleanup, not urgent |

---

## Status guide

| Status | Meaning |
|---|---|
| Waiting | Not started |
| Doing | Being compacted |
| Done | Completed and summary updated |
| Cancelled | No longer needed |

---

## Completion checklist

When a compaction task is done:

- [ ] Update the project's `07_compacted_summary.md`
- [ ] Move raw details to `99_raw_archive.md`
- [ ] Record the change in `08_changelog.md`
- [ ] Mark this queue item as Done
