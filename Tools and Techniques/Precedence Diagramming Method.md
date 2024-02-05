---
tags:
  - tool-technique
  - diagram
  - scheduling
Description: "[[Precedence Diagramming Method#Description|📝]]"
aliases:
  - PDM
---
# Description
Constructing a schedule model in which activities are represented by nodes and are graphically linked by one or more logical relationships to show the sequence in which the activities are to be performed.

**Predecessor** activity — activity that logically comes before a dependent activity in a schedule.
**Successor** activity — dependent activity that logically comes after another activity in a schedule.

## 4 Types of Relationships/Dependencies
| Name | Description | Example |
| ---- | ---- | ---- |
| **Finish-to-start** (FS) | Successor activity cannot start until a predecessor activity has finished. | Installing the operating system on a PC (successor) cannot start until the PC hardware is assembled (predecessor). |
| **Finish-to-finish** (FF) | Successor activity cannot finish until a predecessor activity has finished. | Writing a document (predecessor) is required to finish before editing the document (successor) can finish. |
| **Start-to-start** (SS) | Successor activity cannot start until a predecessor activity has started. | Level concrete (successor) cannot begin until pour foundation (predecessor) begins. |
| **Start-to-finish** (SF) | Successor activity cannot finish until a predecessor activity has started. | A new accounts payable system (successor) has to start before the old accounts payable system can be shut down (predecessor). |
- **FS** is the most commonly used type of precedence relationship.
- **SF** relationship is very rarely used, but is included to present a complete list of the PDM relationship types.
- Two activities can have two logical relationships at the same time (for example, **SS** and **FF**).
- Multiple relationships between the same activities are not recommended, so a decision has to be made to select the relationship with the highest impact.
- Closed loops are also not recommended in logical relationships.
## Example
![[PDM Relationship Types.png]]
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


