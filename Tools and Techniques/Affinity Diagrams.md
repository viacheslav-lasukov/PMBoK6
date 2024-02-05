---
tags:
  - tool-technique
  - diagram
Description: "[[Affinity Diagrams#Description|📝]]"
TechniqueGroup: "[[Data Representation]]"
---
# Description
Allow large numbers of ideas to be classified into groups for review and analysis.
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


