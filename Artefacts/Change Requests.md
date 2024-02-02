---
Section: 4.3.3.4
tags:
  - "#project-document"
  - artefact
Categories:
  - Project Document
Description: Formal proposal to modify any document, deliverable, or baseline. When issues are found while project work is being performed, change requests can be submitted, which may modify project policies or procedures, project or product scope, project cost or budget, project schedule, or quality of the project or product results. Other change requests cover the needed preventive or corrective actions to forestall negative impact later in the project. Any project stakeholder may request a change. Change requests are processed for review and disposition through the Perform Integrated Change Control process.
---
List of  `Change requests` - unapproved changes, before they land in the [[Change Log]]
# Description
`=this.Description`
# Can Be Initiated from
- Inside the project
- Outside the project
# Can Be
- Optional
- Legally/contractually mandated
# May Include
- **Corrective action** — An intentional activity that realigns the performance of the project work with the project management plan.
- **Preventive action** — An intentional activity that ensures the future performance of the project work is aligned with the project management plan.
- **Defect repair** — An intentional activity to modify a nonconforming product or product component.
- **Updates** — Changes to formally controlled project documents, plans, etc., to reflect modified or additional ideas or content.
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
