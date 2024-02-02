---
Section: "9.3.3.1"
tags: "#project-document"
Categories:
  - "Project Document"
Description: ""
---
# Description
Records the team members and their roles and responsibilities for the project. Documentation can include a project team directory and names inserted into the project management plan, such as the project organization charts and schedules.
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
