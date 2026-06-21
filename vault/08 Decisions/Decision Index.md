# Decision Index

This page indexes important studio and project decisions.

```dataview
TABLE date, area, status, related_projects
FROM "vault/08 Decisions"
WHERE type = "decision" AND file.name != "Decision Index"
SORT date DESC
```
