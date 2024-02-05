---
tags:
  - tool-technique
Description: "[[Product Analysis#Description|📝]]"
Section: 5.3.2.5
---
# Description
Can be used to define products and services. It includes asking questions about a product or service and forming answers to describe the use, characteristics, and other relevant aspects of what is going to be delivered.

Each application area has one or more generally accepted methods for translating high-level product or service descriptions into meaningful deliverables. Requirements are captured at a high level and decomposed to the level of detail needed to design the final product.
## Examples
- Product breakdown
- Requirements analysis
- Systems analysis
- Systems engineering
- Value analysis
- Value engineering
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


