---
tags: "process-group"
---
# Processes
```dataview
TABLE WITHOUT ID Section, file.link as "Name"
FROM #process
WHERE ProcessGroup=link(this.file.name)
SORT page
```
# In Adaptive Environments
## Backlog
- Track, review, and regulate progress and performance by maintaining a backlog. The backlog is prioritized by a business representative with help from the project team who estimates and provides information about technical dependencies.
- Work is pulled from the top of the backlog for the next iteration based on business priority and team capacity.
- Requests for change and defect reports are evaluated by the business representative in consultation with the team for technical input and are prioritized accordingly in the backlog of work.
- This single-list-of-work-and-changes approach originated in project environ- ments with very high rates of change that tended to overwhelm any attempts to separate change requests from originally planned work. Combining these work streams into a single backlog that can be easily resequenced provides a single place for stakeholders to manage and control project work, perform change control, and validate scope.
## Metrics
- As prioritized tasks and changes are pulled from the backlog and completed via iterations, trends, and metrics on work performed, change effort and defect rates are calculated. By sampling progress frequently via short iterations, measures of team capacity and progress against the original scope are made by measuring the number of change impacts and defect remediation efforts. This allows estimates of cost, schedule, and scope to be made based on real progress rates and change impacts. These metrics and projections are shared with project stakeholders via trend graphs (information radiators) to communicate progress, share issues, drive continuous improvement activities, and manage stakeholder expectations.