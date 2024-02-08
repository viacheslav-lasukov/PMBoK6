---
KnowledgeArea: "[[13 Stakeholder Management]]"
ProcessGroup: "[[Planning]]"
ToolsTechniques:
EEFs:
OPAs:
tags:
  - "#process"
TimesPerformed: "Throughout the project"
Description: "[[Plan Stakeholder Engagement#Description|📝]]"
Page: 512
Section: "13.2"
---
# Description
Developing approaches to involve project stakeholders based on their needs, expectations, interests, and potential impact on the project.
## Key Benefits
Provides an actionable plan to interact effectively with stakeholders.
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