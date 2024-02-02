---
tags:
  - artefact
  - project-document
Description: Contains complete supporting records for administration of the procurement processes.
---
# Description
`=this.Description`
# Includes
- Statement of work
- Payment information
- Contractor work performance information
- Plans
- Drawings
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
