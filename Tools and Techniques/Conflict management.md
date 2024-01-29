---
page: 348
section: 9.5.2.1
ToolAndTechniqueGroup: "[[Interpersonal and Team Skills]]"
tags:
  - tool-technique
Description: 
Type: ""
---
# Description
## Sources of conflict
- Scarce resources
- Scheduling prioritites
- Personal work styles
## Reducing amount of conflict
* Team ground rules
* Group norms
* Solid project management practices, like communication planning and role definition

When managed properly, differences of opinion can lead to increased creativity and better decision making.
Conflict should be addressed in private.
## Factors that influence conflict resolution include
* Importance and intensity of the conflict
* Time pressure for resolving the conflict
* Relative power of the people involved in the conflict
* Importance of maintaining a good relationship
* Motivation to resolve conflict on a long-term or short-term basis
## Possible techniques for resolving conflict
* Withdraw/avoid
* Smooth/accomodate
* Compromise/reconicle
* Force/direct
* Collaborate/problem solve
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ToolsTechniques, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(ToolsTechniques, link(this.file.name))
GROUP BY ProcessGroup
```

