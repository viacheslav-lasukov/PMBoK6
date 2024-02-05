---
tags:
  - tool-technique
Description: "[[Dependency Determination and Integration#Description|📝]]"
---
# Description
Dependencies may be characterized by the following attributes: mandatory or discretionary, internal or external:
- mandatory external dependencies
- mandatory internal dependencies
- discretionary external dependencies
- discretionary internal dependencies
## Attributes
- **Mandatory** dependencies. Those that are legally or contractually required or inherent in the nature of the work. Often involve physical limitations, such as on a construction project, where it is impossible to erect the superstructure until after the foundation has been built, or on an electronics project, where a prototype has to be built before it can be tested. Are sometimes referred to as hard logic or hard dependencies. Technical dependencies may not be mandatory. The project team determines which dependencies are mandatory during the process of sequencing the activities. Mandatory dependencies should not be confused with assigning schedule constraints in the [[Scheduling Tool]].
- **Discretionary** dependencies. Are sometimes referred to as preferred logic, preferential logic, or soft logic. Are established based on knowledge of best practices within a particular application area or some unusual aspect of the project where a specific sequence is desired, even though there may be other acceptable sequences. For example, generally accepted best practices recommend that during construction, the electrical work should start after finishing the plumbing work. This order is not mandatory and both activities may occur at the same time (in parallel), but performing the activities in sequential order reduces the overall project risk. Should be fully documented since they can create arbitrary total float values and can limit later scheduling options. When [[Fast Tracking]] techniques are employed, these discretionary dependencies should be reviewed and considered for modification or removal. The project team determines which dependencies are discretionary during the process of sequencing the activities.
- **External** dependencies. Involve a relationship between project activities and non-project activities. Are usually outside of the project team's control. For example, the testing activity in a software project may be dependent on the delivery of hardware from an external source, or governmental environmental hearings may need to be held before site preparation can begin on a construction project. The project management team determines which dependencies are external during the process of sequencing the activities.
- **Internal** dependencies. Involve a precedence relationship between project activities and are generally inside the project team's control. For example, if the team cannot test a machine until they assemble it, there is an internal mandatory dependency. The project management team determines which dependencies are internal during the process of sequencing the activities.
# Used in Processes
## By Knowledge Area
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(file.outlinks, link(this.file.name))
GROUP BY KnowledgeArea
```
## By Process Group
```dataview
TABLE rows.file.link as Processes
FROM #process 
WHERE contains(file.outlinks, link(this.file.name))
GROUP BY ProcessGroup
```


