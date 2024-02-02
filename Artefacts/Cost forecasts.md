---
tags:
  - "#project-document"
Categories:
  - Project Document
Description: Either a calculated EAC value or a bottom-up EAC value is documented and communicated to stakeholders.
---
# Description
`=this.Description`
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
