---
tags: "#project-document"
Categories:
  - "Project Document"
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
# Included In
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
```

