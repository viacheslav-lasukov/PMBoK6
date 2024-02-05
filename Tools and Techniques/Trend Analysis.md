---
tags:
  - tool-technique
  - expert-judgment-topic
Description: "[[Trend Analysis#Description|📝]]"
TechniqueGroup: "[[Data Analysis]]"
---
# Description
Is used to forecast future performance based on past results. It looks ahead in the project for expected slippages and warns the project manager ahead of time that there may be problems later in the schedule if established trends persist. This information is made available early enough in the project timeline to give the project team time to analyze and correct any anomalies. The results of trend analysis can be used to recommend preventive actions if necessary.
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


