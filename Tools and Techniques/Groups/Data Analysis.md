---
Description: "Used to organize, assess, and evaluate data and information"
tags:
  - "tool-technique-group"
---
# Tools & Techniques
```dataview
TABLE Type
FROM #tool-technique 
WHERE ToolAndTechniqueGroup=link(this.file.name)
```
