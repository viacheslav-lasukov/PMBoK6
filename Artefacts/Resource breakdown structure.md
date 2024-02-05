---
tags:
  - "#project-document"
Started By:
Description: "[[Resource Breakdown Structure#Description|📝]]"
---
# Description
Hierarchical representation of resources by category and type.
![[Sample Resource Breakdown Structure.png]]
## Examples
- Labor
- Material
- Equipment
- Supplies
## May Include
- Skill level
- Grade level
- Required certifications
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
