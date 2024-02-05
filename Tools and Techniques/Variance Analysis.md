---
tags:
  - tool-technique
Description: "[[Variance Analysis#Description|📝]]"
TechniqueGroup: "[[Data Analysis]]"
---
# Description
Reviews the differences (or variance) between planned and actual performance. This can include duration estimates, cost estimates, resources utilization, resources rates, technical performance, and other metrics. Variance analysis may be conducted in each Knowledge Area based on its particular variables.
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

