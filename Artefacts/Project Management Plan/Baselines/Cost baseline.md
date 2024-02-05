---
Page:
Section: "7.3.3.1"
tags:
  - "#baseline"
  - "artefact"
Description: "[[Cost Baseline#Description|📝]]"
---
# Description
The component of the [[Project Management Plan]].

The approved version of the time-phased project budget, excluding any management reserves, which can only be changed through formal change control procedures. It is used as a basis for comparison to actual results. The cost baseline is developed as a summation of the approved budgets for the different schedule activities.
![[Project Budget Components.png]]
# Components
```dataview
LIST
FROM #baseline-component
WHERE contains(file.inlinks, this.file.link)
```
