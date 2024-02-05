---
tags:
  - tool-technique
Description: "[[Prototypes#Description|📝]]"
Section: 5.2.2.8
---
# Description
Obtaining early feedback on requirements by providing a model of the expected product before actually building it.

Prototypes allow stakeholders to experiment with a model of the final product rather than being limited to discussing abstract representations of their requirements. Prototypes support the concept of progressive elaboration in iterative cycles of mock-up creation, user experimentation, feedback generation, and prototype revision. When enough feedback cycles have been performed, the requirements obtained from the prototype are sufficiently complete to move to a design or build phase.
## Examples
- small-scale products
- computer generated 2D and 3D models
- mock-ups
- simulations
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


