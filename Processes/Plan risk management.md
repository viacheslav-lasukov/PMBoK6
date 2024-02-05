---
KnowledgeArea: "[[11 Risk Management]]"
ProcessGroup: "[[Planning]]"
ToolsTechniques: 
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Once or at predefined points in the project
Description: "[[Plan Risk Management#Description|📝]]"
Page: 401
Section: "11.1"
---
# Description
Defining how to conduct risk management activities for a project.
## Key Benefits
Ensures that the degree, type, and visibility of risk management are proportionate to both risks and the importance of the project to the organization and other stakeholders.
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