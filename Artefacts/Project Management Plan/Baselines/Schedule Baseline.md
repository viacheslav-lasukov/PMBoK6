---
Page: 217
Section: "6.5.3.1"
Components:
tags:
  - "#baseline"
Category: "Baseline"
---
# Description
The approved version of a schedule model that can be changed only through formal change control procedures and is used as a basis for comparison to actual results. It is accepted and approved by the appropriate stakeholders as the schedule baseline with baseline start dates and baseline finish dates. During [[Monitoring and Controlling]], the approved baseline dates are compared to the actual start and finish dates to determine if variances have occurred.
# Components
```dataview
LIST
FROM #baseline-component
WHERE contains(file.inlinks, this.file.link)
```


Meta:
* drives Bar charts (gantt charts)
* drives Milestone charts
* drives [Project schedule network diagram](Project%20schedule%20network%20diagram.md)


