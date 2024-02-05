---
KnowledgeArea: "[[9 Resource Management]]"
ProcessGroup: "[[Executing]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Throughout the project
Description: "[[Develop Team#Description|📝]]"
Page: 336
Section: "9.4"
---
# Description
Improving competencies, team member interaction, and the overall team environment to enhance project performance.
## Key Benefits
Results in improved teamwork, enhanced [[Interpersonal and Team Skills]] and competencies, motivated employees, reduced attrition, and improved overall project performance.
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