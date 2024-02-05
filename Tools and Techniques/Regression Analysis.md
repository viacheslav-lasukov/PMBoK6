---
tags:
  - "tool-technique"
Description: "Analyzes the interrelationships between different project variables that contributed to the project outcomes to improve performance on future projects."
TechniqueGroup: "[[Data Analysis]]"
---
# Description
`=this.Description`
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

