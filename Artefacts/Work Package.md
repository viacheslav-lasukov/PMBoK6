---
Section: "5.4.3.1"
tags:
  - "baseline-component"
Description: ""
---
# Description
The lowest level of the [[Work Breakdown Structure]]. Has a unique identifier. These identifiers provide a structure for hierarchical summation of costs, schedule, and resource information and form a [[code of accounts]]. Each work package is part of a [[Control Account]].
## Example
![[Sample WBS Decomposed Down Through Work Packages.png]]
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
