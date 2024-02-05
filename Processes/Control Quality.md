---
KnowledgeArea: "[[8 Quality Management]]"
ProcessGroup: "[[Monitoring and Controlling]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Throughout the project
Description: "[[Control Quality#Description|📝]]"
Page: 298
Section: "8.3"
---
# Description
Monitoring and recording results of executing the [[8 Quality Management]] activities in order to assess performance and ensure the project outputs are complete, correct, and meet customer expectations.
## Key Benefits
Verifying that project deliverables and work meet the requirements specified by key stakeholders for final acceptance. Determines if the project outputs do what they were intended to do. Those outputs need to comply with all applicable standards, requirements, regulations, and specifications.
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