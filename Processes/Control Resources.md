---
KnowledgeArea: "[[9 Resource Management]]"
ProcessGroup: "[[Monitoring and Controlling]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Control Resources#Description|📝]]"
Page: 352
Section: "9.6"
---
# Description
Ensuring that the physical resources assigned and allocated to the project are available as planned, as well as monitoring the planned versus actual utilization of resources and taking corrective action as necessary.
## Key Benefits
Ensuring that the assigned resources are available to the project at the right time and in the right place and are released when no longer needed.
## Times Performed
`=this.TimesPerformed`
# Inputs
## Enterprise Environmental Factors
```dataview
TABLE WITHOUT ID rows.file.link as "EEFs", Category
FROM #eef
WHERE contains(this.EEFs, file.link)
GROUP BY Category
```
## Organizational Process Assets
```dataview
TABLE WITHOUT ID rows.file.link as "OPAs", Category
FROM #opa
WHERE contains(this.OPAs, file.link)
GROUP BY Category
```
# Tools & Techniques
```dataview
TABLE WITHOUT ID TechniqueGroup as "Group", rows.file.link as "Tools & Techniques"
FROM #tool-technique
WHERE contains(this.ToolsTechniques, file.link)
GROUP BY TechniqueGroup
```
## [[Expert Judgment]]
- 
## [[Meetings]]
- 
# Outputs
- 