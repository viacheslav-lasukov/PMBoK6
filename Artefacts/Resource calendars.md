---
Section: "9.2.1.2"
tags:
  - "#project-document"
Description: "[[Resource Calendars#Description|📝]]"
---
# Description
Identifies the working days, shifts, start and end of normal business hours, weekends, and public holidays when each specific resource is available. Information on which resources (such as team resource, equipment, and material) are potentially available during a planned activity period is used for estimating resource utilization. Resource calendars also specify when, and for how long, identified team and physical resources will be available during the project. This information may be at the activity or project level. This includes consideration of attributes such as resource experience and/or skill level, as well as various geographical locations.
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
