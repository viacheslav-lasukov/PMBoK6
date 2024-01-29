---
tags:
  - "#project-document"
Categories:
  - Project Document
Started By:
---
# Description
Hierarchical representation of resources by category and type.
![[Sample Resource Breakdown Structure.png]]
# Categories
- Labor
- Material
- Equipment
- Supplies
## Types
- Skill level
- Grade level
- Required certifications
# Included In
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
```
