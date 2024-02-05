---
tags:
  - "tool-technique"
Description: "[[Multicriteria Decision Analysis#Description|📝]]"
TechniqueGroup: "[[Decision-Making]]"
---
# Description
Uses a decision matrix to provide a systematic analytical approach for establishing criteria, such as risk levels, uncertainty, and valuation, to evaluate and rank many ideas.
## Examples
- Prioritization matrix
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


