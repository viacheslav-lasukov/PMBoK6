---
tags:
  - "tool-technique"
Description: "Interacting with others to exchange information and develop contacts. Networks provide project managers and their teams with access to informal organizations to solve problems, influence actions of their stakeholders, and increase stakeholder support for the work and outcomes of the project, thus improving performance."
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

