---
KnowledgeArea: "[[11 Risk Management]]"
ProcessGroup: "[[Monitoring and Controlling]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Monitor Risks#Description|📝]]"
Page: 452
Section: "11.7"
---
# Description
Monitoring the implementation of agreed-upon risk response plans, tracking identified risks, identifying and analyzing new risks, and evaluating risk process effectiveness throughout the project.
## Key Benefits
Enables project decisions to be based on current information about overall project risk exposure and individual project risks.
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