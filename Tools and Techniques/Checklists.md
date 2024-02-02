---
page: .nan
section: ""
ToolAndTechniqueGroup: "[[Data Gathering]]"
tags:
  - tool-technique
Description: A list of items, actions, or points to be considered. It is often used as a reminder. Risk checklists are developed based on historical information and knowledge that has been accumulated from similar projects and from other sources of information. They are an effective way to capture lessons learned from similar completed projects, listing specific individual project risks that have occurred previously and that may be relevant to this project. The organization may maintain a risk checklist based on its own completed projects or may use generic risk checklists from the industry. While a checklist may be quick and simple to use, it is impossible to build an exhaustive one, and care should be taken to ensure the checklist is not used to avoid the effort of proper risk identification. The project team should also explore items that do not appear on the checklist. Additionally, the checklist should be reviewed from time to time to update new information as well as remove or archive obsolete information.
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

