---
tags:
  - "tool-technique"
Description: "[[Autocratic Decision Making#Description|📝]]"
TechniqueGroup: "[[Decision-Making]]"
---
# Description
One individual takes responsibility for making the decision for the group.
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

