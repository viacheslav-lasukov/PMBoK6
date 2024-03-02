---
tags:
  - "tool-technique"
  - "diagram"
  - "scheduling"
Description: "[[Precedence Diagramming Method#Description|📝]]"
aliases:
  - "PDM"
---
# Description
Constructing a [[Schedule Model]] in which activities are represented by nodes and are graphically linked by one or more logical relationships to show the sequence in which the activities are to be performed.

Precedence Relationship — a logical dependency between activities.
## Types of Relationships/Dependencies
| Name | Description | Example |
| ---- | ---- | ---- |
| **Finish-to-start** (FS) | [[Successor Activity]] cannot start until a [[Predecessor Activity]] has finished. | Installing the operating system on a PC (successor) cannot start until the PC hardware is assembled (predecessor). |
| **Finish-to-finish** (FF) | [[Successor Activity]] cannot finish until a [[Predecessor Activity]] has finished. | Writing a document (predecessor) is required to finish before editing the document (successor) can finish. |
| **Start-to-start** (SS) | [[Successor Activity]] cannot start until a [[Predecessor Activity]] has started. | Level concrete (successor) cannot begin until pour foundation (predecessor) begins. |
| **Start-to-finish** (SF) | [[Successor Activity]] cannot finish until a [[Predecessor Activity]] has started. | A new [[Accounts Payable System]] (successor) has to start before the old [[Accounts Payable System]] can be shut down (predecessor). |
- **FS** is the most commonly used type of precedence relationship.
- **SF** relationship is very rarely used, but is included to present a complete list of the PDM relationship types.
- Two activities can have two logical relationships at the same time (for example, **SS** and **FF**).
- Multiple relationships between the same activities are not recommended, so a decision has to be made to select the relationship with the highest impact.
- Closed loops are also not recommended in logical relationships.
## Example
![[PDM Relationship Types.png]]
