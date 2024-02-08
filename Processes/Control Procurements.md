---
KnowledgeArea: "[[12 Procurement Management]]"
ProcessGroup: "[[Monitoring and Controlling]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Control Procurements#Description|📝]]"
Page: 492
Section: "12.3"
---
# Description
Managing procurement relationships; monitoring contract performance, and making changes and corrections as appropriate; and closing out contracts.
## Key Benefits
Ensures that both the seller's and buyer's performance meet the project's requirements according to the terms of the legal agreement.
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