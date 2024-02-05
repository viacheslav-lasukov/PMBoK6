---
tags:
  - "tool-technique"
Description: "[[Meetings#Description|📝]]"
---
# Description

## Types
- Formal/informal
- Format: face-to-face/virtual
## Attendees
- [[SME]]
- Team members
- Stakeholders
## Meetings
```dataview
LIST
FROM #meeting
SORT file.name
```
# Uses
- [[Meeting Log]]
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(file.outlinks, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(file.outlinks, link(this.file.name))
GROUP BY ProcessGroup
```


