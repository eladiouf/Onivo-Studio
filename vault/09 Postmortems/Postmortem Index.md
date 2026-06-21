# Postmortem Index

This page indexes studio and project postmortems.

```dataview
TABLE date, status, related_projects
FROM "vault/09 Postmortems"
WHERE type = "postmortem" AND file.name != "Postmortem Index"
SORT date DESC
```
