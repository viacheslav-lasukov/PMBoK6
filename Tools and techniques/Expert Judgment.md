---
tags: "tool-technique"
section: "4.1.2.1"
Description: "Judgment provided based upon expertise in an application area, Knowledge Area, discipline, industry, etc., as appropriate for the activity being performed. Such expertise may be provided by any group or person with specialized education, knowledge, skill, experience, or training."
Type: ""
---
# Description
`=this.Description`
# Topics
```dataview
LIST
FROM #expert-judgment-topic
```
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ToolsTechniques, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ToolsTechniques, link(this.file.name))
GROUP BY ProcessGroup
```