---
Page: 148
Section: 5.2.3.2
tags:
  - "#project-document"
Categories:
  - Project Document
Description: A grid that links product requirements from their origin to the deliverables that satisfy them. Helps ensure that each requirement adds business value by linking it to the business and project objectives.
---
# Description
`=this.Description`
# Includes
- Business needs, opportunities, goals, and objectives
- Project objectives
- Project scope and [[WBS]] deliverables
- Product design
- Product development
- Test strategy and test scenarios  
- High-level requirements to more detailed requirements
# Attributes
- Unique identifier
- Description
- Rationale for inclusion
- Owner
- Source
- Priority
- Version
- Current status (active, cancelled, deferred, added, approved, assigned, completed)
- Status date
- Stability
- Complexity
- Acceptance criteria
# Example
![[Pasted image 20240129185825.png]]
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
