---
KnowledgeArea: "[[13 Stakeholder Management]]"
ProcessGroup: "[[Executing]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Throughout the project
Description: "[[Manage Stakeholder Engagement#Description|📝]]"
Page: 523
Section: "13.3"
---
# Description
Communicating and working with stakeholders to meet their needs and expectations, address issues, and foster appropriate stakeholder involvement.
## Key Benefits
Allows the project manager to increase support and minimize resistance from stakeholders.
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