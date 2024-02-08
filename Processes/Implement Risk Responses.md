---
KnowledgeArea: "[[11 Risk Management]]"
ProcessGroup: "[[Executing]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Implement Risk Responses#Description|📝]]"
Page: 449
Section: "11.6"
---
# Description
Implementing agreed-upon [[Plan Risk Responses|risk response plans]].
## Key Benefits
Ensures that agreed-upon risk responses are executed as planned in order to address overall project risk exposure, minimize individual project threats, and maximize individual project opportunities.
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