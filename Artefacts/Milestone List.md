---
tags:
  - "#project-document"
Description: "[[Milestone List#Description|📝]]"
---
# Description
Milestone — significant point or event in a project. A milestone list identifies all project milestones and indicates whether the milestone is mandatory, such as those required by contract, or optional, such as those based on [[Historical Information]].
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


