---
tags:
  - tool-technique
Description: "[[Resource Optimization#Description|📝]]"
---
# Description
Is used to adjust the start and finish dates of activities to adjust planned resource use to be equal to or less than [[Team Resource Availability]].
## Examples
### Resource Leveling
Start and finish dates are adjusted based on resource constraints with the goal of balancing the demand for resources with the available supply.

Can be used when shared or critically required resources are available only at certain times or in limited quantities, or are over-allocated, such as when a resource has been assigned to two or more activities during the same time period, or there is a need to keep resource usage at a constant level.

Can often cause the original critical path to change.
![[Resource Leveling.png]]

### Resource Smoothing
Adjusts the activities of a [[schedule model]] such that the requirements for resources on the project do not exceed certain predefined resource limits.

As opposed to resource leveling, the project's critical path is not changed and the completion date may not be delayed.

Activities may only be delayed within their free and total float.