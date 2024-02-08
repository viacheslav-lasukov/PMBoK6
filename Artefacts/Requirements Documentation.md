---
Page: 147
Section: "5.2.3.1"
tags:
  - "#project-document"
  - "expert-judgment-topic"
Description: "[[Requirements Documentation#Description|📝]]"
---
# Description
Describes how individual requirements meet the business need for the project. Requirements may start out at a high level and become progressively more detailed as more information about the requirements is known. Before being baselined, requirements need to be unambiguous (measurable and testable), traceable, complete, consistent, and acceptable to key stakeholders. The format of the requirements document may range from a simple document listing all the requirements categorized by stakeholder and priority, to more elaborate forms containing an executive summary, detailed descriptions, and attachments.
# Classification
- **Business requirements** — Higher-level needs of the organization as a whole, such as the business issues or opportunities, and reasons why a project has been undertaken.
- **Stakeholder requirements** — Needs of a stakeholder or stakeholder group.
- **Solution requirements** — Features, functions, and characteristics of the product, service, or result that will meet the business and stakeholder requirements.
	- **Functional** — Behaviors of the product.
		- Actions
		- Processes
		- Data
		- Interactions
	- **Nonfunctional** — Supplement functional requirements and describe the environmental conditions or qualities required for the product to be effective.
		- Reliability
		- Security
		- Performance
		- Safety
		- Level of service
		- Supportability
		- Retention/purge
- **Transition and readiness requirements** — Temporary capabilities, such as data conversion and training requirements, needed to transition from the current as-is state to the desired future state.
- **Project requirements** — Actions, processes, or other conditions the project needs to meet.
	- Milestone dates
	- Contractual obligations
	- Constraints
- **Quality requirements** — Any condition or criteria needed to validate the successful completion of a project deliverable or fulfillment of other project requirements.
	- Tests
	- Certifications
	- Validations

constraints described in [[Requirements Management Plan]]
drives [[Requirements Traceability Matrix]]
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
