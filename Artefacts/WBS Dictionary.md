---
Section: "5.4.3.1"
tags:
  - "baseline-component"
Description: "[[WBS Dictionary#Description|📝]]"
---
# Description
A document that provides detailed [[Deliverables|deliverable]], activity, and scheduling information about each component in the [[Work Breakdown Structure]]. The **WBS dictionary** is a document that supports the [[Work Breakdown Structure]]. Most of the information included in the **WBS dictionary** is created by other processes and added to this document at a later stage.
## Information Included
- Code of account identifier
- Description of work
- Assumptions and constraints
- Responsible organization
- Schedule milestones
- Associated schedule activities
- Resources required
- Cost estimates
- Quality requirements
- Acceptance criteria
- Technical references
- Agreement information
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```