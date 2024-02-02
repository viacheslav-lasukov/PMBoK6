---
Page: 
Section: 5.4.3.1
Components:
  - "[[Project Scope Statement]]"
  - "[[WBS]]"
  - "[[Work Package]]"
  - "[[Planning Package]]"
  - "[[WBS Dictionary]]"
tags:
  - "#baseline"
Categories:
  - Baseline
Description: ""
---
# Description
The approved version of a scope statement, [[WBS]], and its associated [[WBS Dictionary]], which can be changed only through formal [[Change Control Procedures]] and is used as a basis for comparison.
# Components
```dataview
LIST
FROM #baseline-component
WHERE contains(file.inlinks, this.file.link)
```
