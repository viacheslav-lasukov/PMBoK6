---
tags:
  - "#project-document"
Categories:
  - Project Document
Description: Forecasts of estimates or predictions of conditions and events in the project's future based on information and knowledge available at the time of the forecast.
---
# Description
`=this.Description`
# Based on
[[Work Perfomance Information]]
# Can Include
- EV performance (see. [[Earned Value Analysis|EVM]])
- Schedule reserve
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
