---
Description: "Used to select a course of action from different alternatives"
tags:
  - "tool-technique-group"
---
# Tools & Techniques
```dataview
TABLE Type
FROM #tool-technique 
WHERE ToolAndTechniqueGroup=link(this.file.name)
```

