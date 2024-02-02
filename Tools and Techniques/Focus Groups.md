---
page: .nan
section: ""
ToolAndTechniqueGroup: "[[Data Gathering]]"
tags:
  - tool-technique
Description: Focus groups bring together prequalified stakeholders and subject matter experts to learn about their expectations and attitudes about a proposed product, service, or result. A trained moderator guides the group through an interactive discussion designed to be more conversational than a one-on-one interview.
Type: Meeting
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

