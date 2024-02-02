---
Description: "[[Initial Meeting#Description|📝]]"
---
# Description
With key stakeholders, identify the project objectives, success criteria, key [[Deliverables]], high-level requirements, summary milestones, and other summary information.
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

