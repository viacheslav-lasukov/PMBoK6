---
page: .nan
section: "5.2.2.2"
tags:
  - "tool-technique"
Description: "[[Interviews#Description|📝]]"
TechniqueGroup: "[[Data Gathering]]"
---
# Description
A formal or informal approach to elicit information from stakeholders by talking to them directly. It is typically performed by asking prepared and spontaneous questions and recording the responses. Often conducted on an individual basis between an interviewer and an interviewee, but may involve multiple interviewers and/or multiple interviewees. Interviewing experienced project participants, sponsors, other executives, and subject matter experts can aid in identifying and defining the features and functions of the desired product deliverables. Interviews are also useful for obtaining confidential information.
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

