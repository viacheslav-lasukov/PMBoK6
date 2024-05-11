---
tags:
  - swebok/ka
---
# Fundamentals
```dataview
LIST
FROM #swebok/fundamental 
WHERE SWEBOK_KA=this.file.link
```
# Topics
```dataview
LIST rows.file.link
FROM #swebok/subtopic
WHERE SWEBOK_Topic.SWEBOK_KA=this.file.link
GROUP BY SWEBOK_Topic
```
# Practical Considerations
```dataview
LIST
FROM #swebok/practical-consideration
WHERE SWEBOK_KA=this.file.link
```
# Tools
