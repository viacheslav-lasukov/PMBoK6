---
tags:
  - tool-technique
  - expert-judgment-topic
Description: 
aliases:
  - EVM
Learn More:
  - Practice Standard for Earned Value Managemen
TechniqueGroup: "[[Data Analysis]]"
---
# Description
Compares the [[Performance Measurement Baseline]] to the actual schedule and cost performance. integrates the [[Scope Baseline]] with the [[Cost Baseline]] and [[Schedule Baseline]] to form the [[Performance Measurement Baseline]].
# Dimensions
## Planned Value
Authorized budget assigned to scheduled work. Authorized budget planned for the work to be accomplished for an activity or [[Work Breakdown Structure]] component, not including management reserve. This budget is allocated by phase over the life of the project, but at a given point in time, planned value defines the physical work that should have been accomplished. The total of the PV is sometimes referred to as the performance measurement baseline (PMB). The total planned value for the project is also known as budget at completion (BAC).
## Earned Value
Measure of work performed expressed in terms of the budget authorized for that wrk. The budget associated with the authorized work that has been completed. The EV being measured needs to be related to the PMB, and the EV measured cannot be greater than the authorized PV budget for a component. The EV is often used to calculate the percent complete of a project. Progress measurement criteria should be established for each [[Work Breakdown Structure]] component to measure work in progress. Project managers monitor EV, both incrementally to determine current status and cumulatively to determine the long-term performance trends.
## Actual Cost
Realized cost incurred for the work performed on an activity during a specific time period. The total cost incurred in accomplishing the work that the EV measured. The AC needs to correspond in definition to what was budgeted in the PV and measured in the EV (e.g., direct hours only, direct costs only, or all costs including indirect costs). The AC will have no upper limit; whatever is spent to achieve the EV will be measured.
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

