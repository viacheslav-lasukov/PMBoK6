---
Section: 5.4.3.1
tags:
  - baseline-component
Category: Baseline Component
---
# Description
A document that provides detailed deliverable, activity, and scheduling information about each component in the WBS. The WBS dictionary is a document that supports the [[WBS]]. Most of the information included in the WBS dictionary is created by other processes and added to this document at a later stage.
# Included In
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
```
# Includes
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