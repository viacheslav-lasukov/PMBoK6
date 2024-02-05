---
KnowledgeArea: "[[8 Quality Management]]"
ProcessGroup: "[[Executing]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Throughout the project
Description: "[[Manage Quality#Description|📝]]"
Page: 288
Section: "8.2"
---
# Description
Translating the [[quality management plan]] into executable quality activities that incorporate the organization's quality policies into the project. Uses the data and results from the [[Control Quality]] process to reflect the overall quality status of the project to the stakeholders.
## Key Benefits
Increases the probability of meeting the quality objectives as well as identifying ineffective processes and causes of poor quality.
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