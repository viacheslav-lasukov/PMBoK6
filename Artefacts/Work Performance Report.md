---
Description: The physical or electronic representation of work performance information intended to generate decisions, actions, or awareness. They are circulated to the project stakeholders through the communication processes as defined in the project communications management plan.
---
# Description
`=this.Description`
# Examples
- Status report
- Progress report
# Can Contain
- Earned value graphs (see. [[Earned Value Analysis]])
- Trend lines and forecasts (see. [[Trend Analysis]])
- [[Iteration Burndown Chart]]
- Defect histogram
- Contract performance information
- Risk summaries
# Can Be Presented as
- Dashboards
- Heat reports
- Stop light charts
# Examples
- Resource availability
- Schedule and cost data
- EV reports (see. [[Earned Value Analysis|EVM]])
- [[Iteration Burndown Chart]]
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
