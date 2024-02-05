---
tags:
  - tool-technique
Description: "[[Observation, Conversation#Description|📝]]"
TechniqueGroup: "[[Interpersonal and Team Skills]]"
---
# Description
Provides a direct way of viewing individuals in their environment and how they perform their jobs or tasks and carry out processes. It is particularly helpful for detailed processes when the people who use the product have difficulty or are reluctant to articulate their requirements. Observation is also known as “job shadowing.” It is usually done externally by an observer viewing a business expert performing a job. It can also be done by a “participant observer” who actually performs a process or procedure to experience how it is done to uncover hidden requirements.
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


