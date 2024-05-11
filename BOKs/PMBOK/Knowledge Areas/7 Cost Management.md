---
tags:
  - pmbok6/knowledge-area
page: 231
aliases:
  - Cost Management
---
# Processes
```dataview
LIST
FROM #pmbok6/process 
WHERE KnowledgeArea=link(this.file.name)
SORT file.name
```
# Key Concepts
- Project Cost Management is primarily concerned with the cost of the [[Resource]]s needed to complete [[Activity|Activities]], but it should also consider the effect of decisions on the subsequent recurring cost of using, maintaining, and supporting [[deliverables]].
	- For example, limiting the number of design reviews can reduce the cost of the [[Project]] but could increase the resulting [[Product]]'s operating costs.
- Different stakeholders will measure project costs in different ways and at different times. Stakeholder requirements for managing costs should be considered explicitly.
	- For example, the cost of an acquired item may be measured when the [[Acquisition]] decision is made or committed, the order is placed, the item is delivered, or the [[Actual Cost|AC]] is incurred or recorded for project accounting purposes.
- Predicting and analyzing the prospective financial performance of the [[Product]] may be performed outside the [[Project]], or it may be part of [[7 Cost Management|Cost Management]].
# Trends and Emerging Practices
Earned Schedule (**ES**) is an extension to the theory and practice of [[Earned Value Analysis|EVA]]. **ES** theory replaces the schedule [[Variance]] measures used in traditional [[Earned Value Analysis|EVA]] (**[[Earned Value|EV]] − [[Planned Value|PV]]**) with **ES** and actual time (**AT**). Using the alternate equation for calculating [[Schedule Variance]] **ES − AT**, if the amount of earned schedule is greater than 0, then the project is considered ahead of schedule. In other words, the project earned more than planned at a given point in time. The [[Schedule Performance Index|SPI]] (**SPI**) using earned schedule metrics is **ES/AT**. This indicates the efficiency with which work is being accomplished. **ES** theory also provides formulas for forecasting the project completion date, using **ES**, actual time, and estimated duration.
# [[Tailoring]] Considerations
| Aspect | Useful Questions |
| ---- | ---- |
| [[Knowledge Management]]  | Does the organization have a formal [[Knowledge Management]]  and financial databases repository that a project manager is required to use and is readily accessible? |
| Estimating and budgeting | Does the organization have existing formal or informal cost estimating and budgeting-related policies, procedures, and guidelines? |
| [[Earned Value|EV]] management | Does the organization use [[Earned Value|EV]] management in managing projects? |
| Use of [[Agile Life Cycle\|agile]] approach | Does the organization use [[Agile Life Cycle\|agile]] methodologies in managing projects? How does this impact cost estimating? |
| Governance | Does the organization have formal or informal [[Audit]] and governance policies, procedures, and guidelines? |
# In [[Agile Life Cycle|Agile]] Environments
Projects with high degrees of uncertainty or those where the scope is not yet fully defined may not benefit from detailed cost calculations due to frequent changes. Instead, lightweight estimation methods can be used to generate a fast, high-level [[Forecast]] of project labor costs, which can then be easily adjusted as changes arise. Detailed estimates are reserved for short-term planning horizons in a just-in-time fashion.
In cases where high-variability projects are also subject to strict budgets, the scope and schedule are more often adjusted to stay within cost constraints.