---
page: .nan
section: ""
tags:
  - "tool-technique"
Description: "Reviewing and assessing any relevant documented information. Elicit requirements by analyzing existing documentation and identifying information relevant to the requirements."
TechniqueGroup: "[[Data Analysis]]"
---
# Description
`=this.Description`
# Examples of Documents
- [[Agreements]]
- Business plan
- Business process or interface documentation
- Business rules repositories
- Current process flows
- Marketing literature
- Problem/[[Issue Log]]
- [[Policies, Processes, Procedures]]
- Regulatory documentation such as laws, codes, or ordinances, etc.
- Requests for proposal
- Use cases
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

