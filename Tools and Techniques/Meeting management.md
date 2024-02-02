---
page: .nan
section: 10.2.2.6
ToolAndTechniqueGroup: "[[Interpersonal and Team Skills]]"
tags:
  - tool-technique
Description: Meeting management is taking steps to ensure meetings meet their intended objectives effectively and efficiently.
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
# Steps for Meeting Planning
- Prepare and distribute the agenda stating the objectives of the meeting.
- Ensure that the meetings start and finish at the published time.
- Ensure the appropriate participants are invited and attend.
- Stay on topic.
- Manage expectations, issues, and conflicts during the meeting.
- Record all actions and those who have been allocated the responsibility for completing the action.