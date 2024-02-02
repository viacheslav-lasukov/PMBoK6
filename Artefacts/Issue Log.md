---
tags:
  - "#project-document"
Categories:
  - Project Document
Description: 
Started By: "[[4.3 Direct and Manage Project Work]]"
---
# Consists of
- Issue type
- Who raised the issue and when
- Description
- Priority
- Who is assigned to the issue
- Target resolution date
- Status
- Final solution
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```

