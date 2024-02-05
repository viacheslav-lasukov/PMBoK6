---
tags:
  - tool-technique
Description: "[[Inspections#Description|📝]]"
---
# Description
Examination of a work product to determine if it conforms to documented standards. The results of **inspections** generally include measurements and may be conducted at any level. The results of a single activity can be inspected, or the final product of the project can be inspected. **Inspections** may be called reviews, peer reviews, [[Audits]], or walkthroughs. In some application areas, these terms have narrow and specific meanings. **Inspections** also are used to verify defect repairs.
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


