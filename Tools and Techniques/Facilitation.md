---
page: .nan
section: ""
tags:
  - tool-technique
  - expert-judgment-topic
Description: "[[Facilitation#Description|📝]]"
TechniqueGroup: "[[Interpersonal and Team Skills]]"
---
# Description
Facilitation is the ability to effectively guide a group event to a successful decision, solution, or conclusion. A facilitator ensures that there is effective participation, that participants achieve a mutual understanding, that all contributions are considered, that conclusions or results have full buy-in according to the decision process established for the project, and that the actions and agreements achieved are appropriately dealt with afterward.

It is used with focused sessions that bring key stakeholders together to define product requirements. Workshops can be used to quickly define cross- functional requirements and reconcile stakeholder differences. Because of their interactive group nature, well-facilitated sessions can build trust, foster relationships, and improve communication among the participants, which can lead to increased stakeholder consensus. In addition, issues can be discovered earlier and resolved more quickly than in individual sessions.

## Facilitation skills are used in the following situations
- **Joint application design/development** (JAD). JAD sessions are used in the software development industry. These facilitated sessions focus on bringing business subject matter experts and the development team together to gather requirements and improve the software development process.
- **Quality function deployment** (QFD). In the manufacturing industry, helps determine critical characteristics for new product development. QFD starts by collecting customer needs, also known as voice of the customer (VOC). These needs are then objectively sorted and prioritized, and goals are set for achieving them.
- **[[User Stories]]**. Short, textual descriptions of required functionality, are often developed during a requirements workshop. User stories describe:
	- the stakeholder role, who benefits from the feature (role)
	- what the stakeholder needs to accomplish (goal)
	- the benefit to the stakeholder (motivation)
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

