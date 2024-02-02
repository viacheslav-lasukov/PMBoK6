---
tags:
  - "#project-document"
Categories:
  - "Project Document"
Started By:
Description: ""
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
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
