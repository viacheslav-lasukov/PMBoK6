---
tags:
  - "tool-technique"
Description: "[[Voting#Description|📝]]"
TechniqueGroup: "[[Decision-Making]]"
---
# Description
A collective decision-making technique and an assessment process having multiple alternatives with an expected outcome in the form of future actions. These techniques can be used to generate, classify, and prioritize product requirements.
## Examples
- **Unanimity** — A decision that is reached whereby everyone agrees on a single course of action.
- **Majority** — A decision that is reached with support obtained from more than 50% of the members of the group. Having a group size with an uneven number of participants can ensure that a decision will be reached, rather than resulting in a tie.
- **Plurality** — A decision that is reached whereby the largest block in a group decides, even if a majority is not achieved. This method is generally used when the number of options nominated is more than two.
- **Fist of five** (**Fist to five**). [[project manager]] asks the team to show their level of support for a decision by holding up a closed fist (indicating no support) up to five fingers (indicating full support). If a team member holds up fewer than three fingers, the team member is given the opportunity to discuss any objections with the team. The project manager continues the fist-of-five process until the team achieves consensus (everyone holds up three or more fingers) or agrees to move on to the next decision.
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


