---
tags:
  - tool-technique
Description: "[[Alternatives Analysis#Description|📝]]"
TechniqueGroup: "[[Data Analysis]]"
---
# Description
Is used to:
- select the corrective actions or a combination of corrective and preventive actions to implement when a deviation occurs.
- compare:
	- various levels of resource capability or skills
	- scheduling compression techniques
	- different tools (manual versus automated)
- make, rent, or buy decisions regarding the resources
- reviewe strategic funding options:
	- self-funding
	- funding with equity
	- funding with debt
- choose a way to acquire project resources:
	- making
	- purchasing
	- renting
	- leasing
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


