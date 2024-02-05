---
tags:
  - tool-technique
Description: "[[Rolling Wave Planning#Description|📝]]"
---
# Description
Iterative planning technique in which the work to be accomplished in the near term is planned in detail, while work further in the future is planned at a higher level. It is a form of progressive elaboration applicable to [[Work Package]]s, [[Planning Package]]s, [[Release Planning]] when using an agile or waterfall approach. Therefore, work can exist at various levels of detail depending on where it is in the [[project life cycle]]. During early strategic planning when information is less defined, [[Work Package]]s may be decomposed to the known level of detail. As more is known about the upcoming events in the near term, [[Work Package]]s can be decomposed into activities.
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


