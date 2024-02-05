---
page: .nan
section: ""
tags:
  - "tool-technique"
Description: "[[Benchmarking#Description|📝]]"
TechniqueGroup: "[[Data Gathering]]"
---
# Description
Involves comparing actual or planned project practices or the project's quality standards to those of comparable projects to identify best practices, generate ideas for improvement, and provide a basis for measuring performance. Benchmarked projects may exist within the performing organization or outside of it, or can be within the same application area or other application area. Benchmarking allows for analogies from projects in a different application area or different industries to be made.
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


