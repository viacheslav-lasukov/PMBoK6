---
KnowledgeArea: "[[10 Communications Management]]"
ProcessGroup: "[[Planning]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Plan Communications Management#Description|📝]]"
Page: 359
Section: "10.1"
---
# Description
Developing an appropriate approach and plan for project communications activities based on the information needs of each stakeholder or group, available organizational assets, and the needs of the project.
## Key Benefits
A documented approach to effectively and efficiently engage stakeholders by presenting relevant information in a timely manner.
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