---
Description: "Used to transfer information between stakeholders"
tags:
  - "tool-technique-group"
---
# Tools & Techniques
```dataview
TABLE Type
FROM #tool-technique 
WHERE ToolAndTechniqueGroup=link(this.file.name)
```

