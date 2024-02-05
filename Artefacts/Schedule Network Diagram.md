---
tags:
  - "#project-document"
  - "diagram"
  - "scheduling"
Description: "[[Schedule Network Diagram#Description|📝]]"
---
# Description
Graphical representation of the logical relationships, also referred to as dependencies, among the project schedule activities.

Can include full project details, or have one or more summary activities. A summary narrative can accompany the diagram and describe the basic approach used to sequence the activities. Any unusual activity sequences within the network should be fully described within the narrative.
## Example
![[Project Schedule Network Diagram.png]]
## Convergence and Divergence
Activities that have multiple predecessor activities indicate a path **convergence**.
Activities that have multiple successor activities indicate a path **divergence**.

Activities with divergence and convergence are at greater risk as they are affected by multiple activities or can affect multiple activities. Activity I is called a path convergence, as it has more than one predecessor, while activity K is called a path divergence, as it has more than one successor.
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```

