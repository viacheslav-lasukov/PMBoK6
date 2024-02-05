---
tags:
  - expert-judgment-topic
---
# Description
# Examples
```dataview
LIST
FROM #diagram
```
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ExpertJudgmentTopic, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ExpertJudgmentTopic, link(this.file.name))
GROUP BY ProcessGroup
```
