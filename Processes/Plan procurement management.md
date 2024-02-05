---
KnowledgeArea: "[[12 Procurement Management]]"
ProcessGroup: "[[Planning]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Once or at predefined points in the project
Description: "[[Plan Procurement Management#Description|📝]]"
Page: 466
Section: "12.1"
---
# Description
Documenting project procurement decisions, specifying the approach and identifying potential sellers.
## Key Benefits
Determines whether to acquire goods and services from outside the project and, if so, what to acquire as well as how and when to acquire it. Goods and services may be procured from other parts of the performing organization or from external sources.
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