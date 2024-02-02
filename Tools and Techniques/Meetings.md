---
tags:
  - tool-technique
Type: Meeting
Description: "[[Meetings#Description|📝]]"
---
# Description

## Types
- Formal/informal
- Format: face-to-face/virtual
- Participants: team members/others
## Meetings
```dataview
LIST
FROM #meeting 
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


