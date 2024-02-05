---
tags:
  - tool-technique
Description: "[[Nominal Group Technique#Description|📝]]"
TechniqueGroup: "[[Interpersonal and Team Skills]]"
---
# Description
Enhances brainstorming with a voting process used to rank the most useful ideas for further brainstorming or for prioritization.
## Steps
1. A question or problem is posed to the group. Each person silently generates and writes down their ideas.
2. The moderator writes down the ideas on a flip chart until all ideas are recorded.
3. Each recorded idea is discussed until all group members have a clear understanding.
4. Individuals vote privately to prioritize the ideas, usually using a scale of 1–5, with 1 being the lowest and 5 being the highest. Voting may take place in many rounds to reduce and focus in on ideas. After each round, the votes are tallied and the highest scoring ideas are selected.

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


