---
page: .nan
section: ""
ToolAndTechniqueGroup: "[[Data Analysis]]"
tags:
  - tool-technique
Description: Is used to determine the basic underlying reason that causes a variance, defect, or risk. A root cause may underlie more than one variance, defect, or risk. It may also be used as a technique for identifying root causes of a problem and solving them. When all root causes for a problem are removed, the problem does not recur.
Type: ""
---
# Description
`=this.Description`
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


