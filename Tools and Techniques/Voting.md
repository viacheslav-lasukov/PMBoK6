---
ToolAndTechniqueGroup: "[[Decision-Making]]"
tags:
  - tool-technique
Description: A collective decision-making technique and an assessment process having multiple alternatives with an expected outcome in the form of future actions. These techniques can be used to generate, classify, and prioritize product requirements.
Type: ""
---
# Description
`=this.Description`
# Examples
- **Unanimity** — A decision that is reached whereby everyone agrees on a single course of action.
- **Majority** — A decision that is reached with support obtained from more than 50% of the members of the group. Having a group size with an uneven number of participants can ensure that a decision will be reached, rather than resulting in a tie.
- **Plurality** — A decision that is reached whereby the largest block in a group decides, even if a majority is not achieved. This method is generally used when the number of options nominated is more than two.
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


