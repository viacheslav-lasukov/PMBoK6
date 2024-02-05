---
page: .nan
section: ""
tags:
  - tool-technique
Description: "[[Mind Mapping#Description|📝]]"
TechniqueGroup: "[[Data Representation]]"
---
# Description
Consolidates ideas created through individual brainstorming sessions into a single map to reflect commonality and differences in understanding and to generate new ideas.
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


