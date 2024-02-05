---
tags:
  - "tool-technique"
  - "expert-judgment-topic"
Description: "Knowledge management tools and techniques connect people so they can work together to create new knowledge, share tacit knowledge, and integrate the knowledge of diverse team members."
---
# Description
`=this.Description`
# Examples
- [[Networking]]
- Communities of practice and special interest groups
- [[Meetings]]
- Work shadowing and reverse shadowing
- Discussion forums
- Knowledge-sharing events (seminars, conferences)
- Workshops including [[Problem Solving]] sessions
- Storytelling
- Creativity and ideas management techniques
- Knowledge fairs and cafes
- Training that involves interation between learners

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


