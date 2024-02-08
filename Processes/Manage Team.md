---
KnowledgeArea: "[[9 Resource Management]]"
ProcessGroup: "[[Executing]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Manage Team#Description|📝]]"
Page: 345
Section: "9.5"
---
# Description
Tracking team member performance, providing feedback, resolving issues, and managing team changes to optimize project performance.
## Key Benefits
Influences team behavior, manages conflict, and resolves issues.
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