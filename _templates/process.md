---
KnowledgeArea:
ProcessGroup:
Section:
tags:
  - process
page:
ToolsTechniques: 
EEFs: 
OPAs:
Outputs:
ExpertJudgmentTopics:
---
# Inputs
### Enterprise Environmental Factors
```dataview
TABLE WITHOUT ID rows.file.link as "EEFs", Type
FROM #eef
WHERE contains(file.inlinks, this.file.link)
GROUP BY Type
```
### Organizational process assets
```dataview
TABLE WITHOUT ID rows.file.link as "OPAs", Category
FROM #opa
WHERE contains(file.inlinks, this.file.link)
GROUP BY Category
```
# Tools & techniques

```dataview
TABLE WITHOUT ID ToolAndTechniqueGroup as "Group", rows.file.link as "Tools & Techniques"
FROM #tool-technique
WHERE contains(file.inlinks, this.file.link)
GROUP BY ToolAndTechniqueGroup
```
## Expert Judgment Topics
```dataview
LIST
FROM #expert-judgment-topic
WHERE contains(file.inlinks, this.file.link)
```
## Meetings
```dataview
LIST
FROM #meeting
WHERE contains(file.inlinks, this.file.link)
```
# Outputs
```dataview
LIST WITHOUT ID Outputs
FLATTEN Outputs
WHERE file.name=this.file.name
```

