---
tags:
  - tool-technique
  - diagram
Description: "[[Context Diagram#Description|📝]]"
Section: 5.2.2.7
---
# Description
Visually depicts the product scope by showing a business system (process, equipment, computer system, etc.), and how people and other systems (actors) interact with it. Shows inputs to the business system, the actor(s) providing the input, the outputs from the business system, and the actor(s) receiving the output.
![[Context Diagram.png]]
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


