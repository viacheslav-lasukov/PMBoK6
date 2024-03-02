---
tags:
  - pmbok6/knowledge-area
page: 271
aliases:
  - Quality Management
---
![[Major Project Quality Management Process Interrelations.png]]
# Processes
```dataview
LIST
FROM #process 
WHERE KnowledgeArea=link(this.file.name)
SORT name
```
# Key Concepts
- Project Quality Management addresses the management of the project and the deliverables of the project. It applies to all projects, regardless of the nature of their deliverables. [[Quality]] measures and techniques are specific to the type of deliverables being produced by the project.
- Failure to meet the [[Quality Requirement]]s can have negative consequences:
	- Meeting [[Customer]] requirements by overworking the project team may result in decreased profits and increased levels of [[Overall Project Risk]]s, employee attrition, errors, or [[Rework]].
	- Meeting project schedule objectives by rushing planned quality inspections may result in undetected errors, decreased profits, and increased post-implementation risks.
- The project manager and team are responsible for managing trade-offs associated with delivering the required levels of both **[[Quality]]** and **[[Grade]]**.
	- **[[Quality]]** is “the degree to which a set of inherent characteristics fulfills requirements” (ISO 9000).
	- **[[Grade]]** is a category assigned to deliverables having the same functional use but different technical characteristics. 
- While a [[Quality]] level that fails to meet [[Quality Requirement]]s is always a problem, a low-[[grade]] [[Product]] may not be a problem.
	- It may not be a problem if a suitable low-[[grade]] [[Product]] (one with a limited number of features) is of high quality (no obvious defects). In this example, the [[Product]] would be appropriate for its general purpose of use.
	- It may be a problem if a high-[[grade]] [[Product]] (one with numerous features) is of low [[Quality]] (many defects). In essence, a high-[[grade]] feature set would prove ineffective and/or inefficient due to low [[Quality]].
- Prevention is preferred over inspection. It is better to design [[Quality]] into deliverables, rather than to find [[Quality]] issues during inspection. The cost of preventing mistakes is generally much less than the cost of correcting mistakes when they are found by inspection or during usage.
- Team may need a working [[Knowledge]] of statistical [[Control]] processes to evaluate [[Data]] contained in the [[8.3 Control Quality]] outputs. The team should know the differences between the following pairs of terms:
	- **Prevention** (keeping errors out of the process) and **inspection** (keeping errors out of the hands of the [[Customer]]);
	- **[[Attribute Sampling]]** (the result either conforms or does not conform) and **variable sampling** (the result is rated on a continuous scale that measures the degree of conformity); and
	- **[[Tolerance]]s** (specified range of acceptable results) and **[[Control Limit]]s** (that identify the boundaries of common [[Variation]] in a statistically stable process or process performance).
- Project managers may need to be familiar with sampling. [[Attribute Sampling]] (the result either conforms or does not conform) and variable sampling (the result is rated on a continuous scale that measures the degree of conformity).
- Many projects establish tolerances and [[Control Limit]]s for project and [[Product]] measurements. Tolerances (the specified range of acceptable results) and [[Control Limit]]s (the boundaries of common [[Variation]] in a statistically stable process or process performance).
- The [[cost of quality]] includes all costs incurred over the life of the [[Product]] by investment in preventing nonconformance to requirements, appraising the [[Products, Services, Results]] for [[Conformance]] to requirements, and failing to meet requirements ([[Rework]]). [[Cost of quality]] is often the concern of [[Program Management]], [[Portfolio Management]], the [[Project Management Office|PMO]], or [[Operation]]s.
- 5 levels of increasingly effective quality management:
	- The most expensive approach is to let the [[Customer]] find the defects. This approach can lead to warranty issues, recalls, loss of reputation, and [[Rework]] costs.
	- Detect and correct the defects before the deliverables are sent to the [[Customer]] as part of the [[8.3 Control Quality|Quality Control]] process. The [[8.3 Control Quality]] process has related costs, which are mainly the appraisal costs and internal failure costs.
	- Use [[8.2 Manage Quality|Quality Assurance]] to examine and correct the process itself and not just special defects.
	- Incorporate [[Quality]] into the planning and designing of the project and [[Product]].
	- Create a culture throughout the organization that is aware and committed to [[Quality]] in processes and [[Product]]s.

# Trends and Emerging Practices
- **[[Customer Satisfaction]]**. Understand, evaluate, define, and manage requirements so that [[Customer]] expectations are met. This requires a combination of [[Conformance]] to requirements (to ensure the project produces what it was created to produce) and fitness for use (the [[Products, Services, Results]] needs to satisfy the real needs). In [[Agile Life Cycle|agile]] environments, [[Stakeholder Engagement]] with the team ensures [[Customer Satisfaction]] is maintained throughout the project.
- **Continual improvement**. The plan-do-check-act (PDCA) cycle is the basis for [[Quality]] improvement as defined by Shewhart and modified by Deming. In addition, [[Quality]] improvement initiatives such as [[Total Quality Management]], [[Six Sigma]], and [[Lean Six Sigma]] may improve both the [[Quality]] of [[Project Management]], as well as the [[Quality]] of the end [[Products, Services, Results]].
- **Management responsibility**. Success requires the participation of all members of the [[Team]]. Management retains, within its responsibility for [[Quality]], a related responsibility to provide suitable [[Resource]]s at adequate capacities.
- **Mutually beneficial partnership with suppliers**. Relationships based on partnership and cooperation with the [[Seller|supplier]] are more beneficial to the organization and to the suppliers than traditional [[Seller|supplier]] management. The organization should prefer long-term relationships over short-term gains. A mutually beneficial relationship enhances the ability for both the organization and the suppliers to create value for each other, enhances the joint responses to [[Customer]] needs and expectations, and optimizes costs and [[Resource]]s.
# [[Tailoring]] Considerations
| Aspect | Useful Questions |
| ---- | ---- |
| Policy compliance and [[Audit]]ing | - What quality policies and procedures exist in the organization?<br>- What quality tools, techniques, and templates are used in the organization? |
| Standards and regulatory compliance | - Are there any specific [[Quality Standards]] in the industry that need to be applied?<br>- Are there any specific governmental, legal, or regulatory [[Constraint]]s that need to be taken into consideration? |
| Continuous improvement | - How will [[Quality]] improvement be managed in the project?<br>- Is it managed at the organizational level or at the level of each project? |
| Stakeholder engagement | Is there a collaborative environment with stakeholders and suppliers? |
# In [[Agile Life Cycle|Agile]] Environments
In order to navigate changes, [[Agile Life Cycle|agile]] methods call for frequent [[Quality]] and review steps built in throughout the project rather than toward the end of the project.

Recurring [[Retrospective]]s regularly check on the effectiveness of the quality processes. They look for the [[Root Cause Analysis|root cause]] of issues then suggest trials of new approaches to improve [[Quality]]. Subsequent retrospectives evaluate any trial processes to determine if they are working and should be continued or new adjusting or should be dropped from use.

In order to facilitate frequent, incremental delivery, [[Agile Life Cycle|agile]] methods focus on small batches of work, incorporating as many elements of project [[Deliverables]] as possible. Small batch systems aim to uncover inconsistencies and [[Quality]] issues earlier in the project life cycle when the overall costs of change are lower.