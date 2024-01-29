---
page: .nan
section: ""
ToolAndTechniqueGroup: "[[Interpersonal and Team Skills]]"
tags:
  - tool-technique
Description: Facilitation is the ability to effectively guide a group event to a successful decision, solution, or conclusion. A facilitator ensures that there is effective participation, that participants achieve a mutual understanding, that all contributions are considered, that conclusions or results have full buy-in according to the decision process established for the project, and that the actions and agreements achieved are appropriately dealt with afterward.
Type: ""
---
# Description
`=this.Description`
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

