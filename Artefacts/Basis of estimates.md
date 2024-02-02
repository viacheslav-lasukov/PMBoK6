---
tags:
  - "#project-document"
Categories:
  - Project Document
Description: The amount and type of additional details supporting the duration estimate vary by application area. Regardless of the level of detail, the supporting documentation should provide a clear and complete understanding of how the duration estimate was derived.
---
# Description
`=this.Description`
# May Include
- Documentation of the basis of the estimate (i.e., how it was developed),
- Documentation of all assumptions made,
- Documentation of any known constraints,
- Indication of the range of possible estimates (e.g., ±10%) to indicate that the duration is estimated between a range of values),
- Indication of the confidence level of the final estimate
- Documentation of individual project risks influencing this estimate.
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
