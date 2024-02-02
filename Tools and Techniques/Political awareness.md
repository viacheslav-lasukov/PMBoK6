---
page: .nan
section: ""
ToolAndTechniqueGroup: "[[Interpersonal and Team Skills]]"
tags:
  - tool-technique
Description: Helps the project manager to plan communications based on the project environment as well as the organization's political environment. Political awareness concerns the recognition of power relationships, both formal and informal, and also the willingness to operate within these structures. An understanding of the strategies of the organization, knowing who wields power and influence in this arena, and developing an ability to communicate with these stakeholders are all aspects of political awareness.
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

