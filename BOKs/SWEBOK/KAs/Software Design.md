---
tags:
  - swebok/ka
---
The process of defining the architecture, components, interfaces, and other characteristics of a system or component, and the result of this process.

Is the software engineering life cycle activity in which [[Software Requirements]] are analyzed in order to produce a description of the [[software]]’s internal structure that will serve as the basis for its construction.

Describes the software architecture: how software is decomposed and organized into components, and the interfaces between those components.\

Describe the components at a level of detail that enables their construction.
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

