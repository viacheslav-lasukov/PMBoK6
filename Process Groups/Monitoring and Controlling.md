---
tags: "process-group"
---
# Processes
```dataview
TABLE
FROM #process 
WHERE ProcessGroup=link(this.file.name)
SORT file.name
```
