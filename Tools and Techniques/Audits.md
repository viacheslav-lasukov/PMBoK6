---
tags:
  - tool-technique
  - expert-judgment-topic
Description: ""
Type: ""
---
# Description
`=this.Description`
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ToolsTechniques, link(this.file.name)) OR contains(ExpertJudgmentTopics, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ToolsTechniques, link(this.file.name)) OR contains(ExpertJudgmentTopics, link(this.file.name))
GROUP BY ProcessGroup
```
