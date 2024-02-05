---
KnowledgeArea: "[[8 Quality Management]]"
ProcessGroup: "[[Planning]]"
ToolsTechniques:
  - "[[Brainstorming]]"
  - "[[Interviews]]"
  - "[[Benchmarking]]"
EEFs: 
OPAs: 
tags:
  - "#process"
TimesPerformed: Once or at predefined points in the project
Description: "[[Plan Quality Management#Description|📝]]"
Page: 277
Section: "8.1"
---
# Description
Identifying quality requirements and/or standards for the project and its [[deliverables]], and documenting how the project will demonstrate compliance with quality requirements and/or standards.
## Key Benefits
Provides guidance and direction on how quality will be managed and verified throughout the project.
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