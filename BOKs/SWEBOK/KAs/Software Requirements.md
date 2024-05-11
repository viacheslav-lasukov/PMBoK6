---
tags:
  - swebok/ka
---
Concerned with the elicitation, analysis, specification, and validation of [[requirement]]s as well as the management of [[Requirement]]s during the whole life cycle of the [[Phenomenons/Software]] [[product]].

[[Requirement]]s express the [[need]]s and [[Constraint]]s placed on a [[Phenomenons/Software]] product that contribute to the [[Solution]] of some real-world problem.
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
Categories:
- Modeling Requirements Tools
- Managing Requirements Tools