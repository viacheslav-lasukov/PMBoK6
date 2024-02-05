---
tags:
  - "tool-technique"
Description: "Acknowledging, clarifying and confirming, understanding, and removing barriers that adversely affect comprehension."
Section: "10.2.2.6"
TechniqueGroup: "[[Interpersonal and Team Skills]]"
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


