---
page: .nan
section: ""
tags:
  - "tool-technique"
Description: "[[Questionnaires and surveys#Description|📝]]"
TechniqueGroup: "[[Data Gathering]]"
---
# Description
Written sets of questions designed to quickly accumulate information from a large number of respondents. Questionnaires and/or surveys are most appropriate with varied audiences, when a quick turnaround is needed, when respondents are geographically dispersed, and where statistical analysis could be appropriate.
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(file.outlinks, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(file.outlinks, link(this.file.name))
GROUP BY ProcessGroup
```


