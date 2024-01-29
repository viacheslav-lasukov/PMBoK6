# Description
`=this.Description`
# Key Benefits
`=this.KeyBenefits`
# Inputs
## Enterprise Environmental Factors
```dataview
TABLE WITHOUT ID rows.file.link as "EEFs", Category
FROM #eef
WHERE contains(this.EEFs, file.link)
GROUP BY Category
```
## Organizational process assets
```dataview
TABLE WITHOUT ID rows.file.link as "OPAs", Category
FROM #opa
WHERE contains(this.OPAs, file.link)
GROUP BY Category
```
# Tools & techniques

```dataview
TABLE WITHOUT ID ToolAndTechniqueGroup as "Group", rows.file.link as "Tools & Techniques"
FROM #tool-technique
WHERE contains(this.ToolsTechniques, file.link)
GROUP BY ToolAndTechniqueGroup
```
## Expert Judgment Topics
```dataview
LIST
FROM #expert-judgment-topic
WHERE contains(this.ExpertJudgmentTopics, file.link)
```
## Meetings
```dataview
LIST
FROM #meeting
WHERE contains(file.inlinks, this.file.link)
```
# Outputs
```dataview
LIST
FLATTEN Outputs
WHERE contains(this.Outputs, file.link)
```

