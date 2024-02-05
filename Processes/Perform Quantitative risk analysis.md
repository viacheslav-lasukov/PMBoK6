---
KnowledgeArea: "[[11 Risk Management]]"
ProcessGroup: "[[Planning]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Throughout the project
Description: "[[Perform Quantitative risk analysis#Description|📝]]"
Page: 428
Section: "11.4"
---
# Description
Numerically analyzing the combined effect of identified individual project risks and other sources of uncertainty on overall project objectives.
## Key Benefits
Quantifies overall project risk exposure and provides additional quantitative risk information to support [[Plan Risk Responses|risk response planning]].
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