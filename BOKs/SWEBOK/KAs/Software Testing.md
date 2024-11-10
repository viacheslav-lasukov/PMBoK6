---
tags:
  - swebok/ka
---
Can be seen as a means for providing information about the functionality and [[Quality Attributes]] and also for identifying faults in those cases where error prevention has not been effective.

Can reveal [[failure]]s, but it is the [[fault]]s that can and must be removed

Consists of the ***dynamic*** verification that a program provides ***expected*** behaviors on a ***finite*** set of test cases, suitably ***selected*** from the usually infinite execution domain.
- ***Dynamic***: Testing always implies executing the program on selected inputs. To be precise, the input value alone is not always sufficient to specify a test, since a complex, nondeterministic system might react to the same input with different behaviors, depending on the system state. The term “input” will be maintained, with the implied convention that its meaning also includes a specified input state in those cases for which it is important. Static techniques are different from and complementary to dynamic testing (see [[Software Quality]] #swebok/ka). It is worth noting that terminology is not uniform among different communities and some use the term “testing” also in reference to static techniques.
- ***Finite***: Even in simple programs, so many test cases are theoretically possible that exhaustive testing could require months or years to execute. This is why, in practice, a complete set of tests can generally be considered infinite, and testing is conducted on a subset of all possible tests, which is determined by risk and prioritization criteria. Testing always implies a tradeoff between limited resources and schedules on the one hand and inherently unlimited test requirements on the other.
- ***Selected***: The many proposed test techniques differ essentially in how the test set is selected, and software engineers must be aware that different selection criteria may yield vastly different degrees of effectiveness. How to identify the most suitable selection criterion under given conditions is a complex problem; in practice, risk analysis techniques and software engineering expertise are applied.
- ***Expected***: It must be possible, although not always easy, to decide whether the observed outcomes of program testing are acceptable or not; otherwise, the testing effort is useless. The observed behavior may be checked against user needs (commonly referred to as testing for validation), against a specification (testing for verification), or, perhaps, against the anticipated behavior from implicit requirements or expectations (see [[Acceptance Testing|Acceptance Tests]]).

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
