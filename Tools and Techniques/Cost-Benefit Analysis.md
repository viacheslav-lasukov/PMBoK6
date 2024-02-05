---
tags:
  - "tool-technique"
Description: "a financial analysis tool used to estimate the strengths and weaknesses of alternatives in order to determine the best alternative in terms of benefits provided. It will help the project manager determine if the planned quality activities are cost effective."
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

