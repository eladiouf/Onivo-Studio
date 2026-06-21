# Meetings Index

Use this page to track review, planning, innovation, and release meetings.

```dataview
TABLE date, meeting_type, status, related_projects
FROM "vault/03 Operations"
WHERE type = "meeting" AND file.name != "Meetings Index"
SORT date DESC
```
