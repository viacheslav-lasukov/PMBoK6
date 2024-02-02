---
ToolAndTechniqueGroup: "[[Data Analysis]]"
tags:
  - tool-technique
Description: Is used to select the corrective actions or a combination of corrective and preventive actions to implement when a deviation occurs.
Type: ""
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


