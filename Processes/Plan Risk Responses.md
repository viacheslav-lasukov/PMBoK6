---
KnowledgeArea: "[[11 Risk Management]]"
ProcessGroup: "[[Planning]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Plan Risk Responses#Description|📝]]"
Page: 437
Section: "11.5"
---
# Description
Developing options, selecting strategies, and agreeing on actions to address overall project risk exposure, as well as to treat individual project risks.
## Key Benefits
Identifies appropriate ways to address overall project risk and individual project risks. Allocates resources and inserts activities into project documents and the project management plan as needed.
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