---
tags: "opa"
Category: "Knowledge Bases"
Type: "OPA"
---
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(OPAs, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(OPAs, link(this.file.name))
GROUP BY ProcessGroup
```


