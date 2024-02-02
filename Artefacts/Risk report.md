---
Page: 418
Section: 11.2.3.2
tags:
  - "#project-document"
Categories:
  - Project Document
Description: Presents information on sources of overall project risk, together with summary information on identified individual project risks.
---
# Description
`=this.Description`
# Includes
- **Sources of overall project risk**, indicating which are the most important drivers of overall project risk exposure
- **Summary information on identified individual project risks**, such as number of identified threats and opportunities, distribution of risks across risk categories, metrics and trends, etc.
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```

described by [Risk Management plan](Risk%20Management%20plan.md)
driven by data [Risk register](Risk%20register.md)  - Risk report re-visualizes this data.

