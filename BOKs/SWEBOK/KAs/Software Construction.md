---
tags:
  - swebok/ka
---
Detailed creation of working software through a combination of [[Coding]], verification, [[Unit Testing]], [[Integration Testing]], and [[debugging]].

Code is the ultimate [[Deliverables]] of a [[software project]].
## Relationships with other #swebok/ka s

| Another #swebok/ka or #discipline                                  | Reason linked                                                                                                                                                                                                                                                                           |
| ------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| - [[Software Design]]<br>- [[Software Testing]]                    | Uses the design output and provides an input to testing (“design” and “testing” in this case referring to the activities, not the KAs). Boundaries between design, construction, and testing (if any) will vary depending on the [[Life Cycle|life cycle]] used in [[Project]] |
| [[Software Configuration Management]]                              | Produces the highest number of configuration items that need to be managed in a [[software]] [[project]] ([[source file]]s, documentation, [[test case]]s, and so on)                                                                                                                   |
| [[Computing Foundations]]                                          | Requires knowledge of algorithms and of coding practices                                                                                                                                                                                                                                |
| [[Disciplines/Project Management\|Project Management]] #discipline | The management of construction can present considerable challenges                                                                                                                                                                                                                      |
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
