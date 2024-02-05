---
KnowledgeArea: "[[13 Stakeholder Management]]"
ProcessGroup: "[[Monitoring and Controlling]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Throughout the project
Description: "[[Monitor Stakeholder Engagement#Description|📝]]"
Page: 530
Section: "13.4"
---
# Description
Monitoring project stakeholder relationships and tailoring strategies for engaging stakeholders through modification of engagement strategies and plans.
## Key Benefits
Maintains or increases the efficiency and effectiveness of stakeholder engagement activities as the project evolves and its environment changes.
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