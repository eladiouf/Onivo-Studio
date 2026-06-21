# Release Board

This page is the navigation surface for release readiness and publication tracking.

```dataview
TABLE project, surface, status, target_window
FROM "vault/07 Publishing"
WHERE type = "release" AND file.name != "Release Board"
SORT target_window ASC
```
