---
tags:
  - tool-technique
  - expert-judgment-topic
Description: Are used to create and connect people to information. effective for sharing simple, unambiguous, codified explicit knowledge.
Type: ""
---
# Description
`=this.Description`
# Examples
- Methods for codifying explicit knowledge; for example, for producing lessons to be learned entries for the lessons learned register
- [[Lessons Learned Register]]
- Library services
- Information gathering, for example, web searches and reading published articles
- [[Project Management Information System]]
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

