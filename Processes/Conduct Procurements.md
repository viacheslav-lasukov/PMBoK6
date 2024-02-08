---
KnowledgeArea: "[[12 Procurement Management]]"
ProcessGroup: "[[Executing]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Conduct Procurements#Description|📝]]"
Page: 482
Section: "12.2"
---
# Description
Obtaining seller responses, selecting a seller, and awarding a contract.
## Key Benefits
Selects a qualified seller and implements the legal agreement for delivery. The end results of the process are the established agreements including formal contracts.
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