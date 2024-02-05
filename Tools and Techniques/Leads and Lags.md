---
tags:
  - tool-technique
  - scheduling
Description: "[[Leads and Lags#Description|📝]]"
---
# Description
| Term | Definition | Example |
| ---- | ---- | ---- |
| Lead | Amount of time a successor activity can be advanced with respect to a predecessor activity. | On a project to construct a new office building, the landscaping could be scheduled to start 2 weeks prior to the scheduled punch list completion. This will be an **FS** with a 2-week **lead**. |
| Lag | Amount of time a successor activity will be delayed with respect to a predecessor activity. | A technical writing team may begin editing the draft of a large document 15 days after they begin writing it. This will be an **SS** relationship with a 15-day **lag**. |
## Example
![[Examples of Lead and Lag.png]]
## Drives
[[Schedule Network Diagram]]
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

