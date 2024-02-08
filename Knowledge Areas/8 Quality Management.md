---
tags:
  - knowledge-area
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
- Project Quality Management addresses the management of the project and the deliverables of the project. It applies to all projects, regardless of the nature of their deliverables. Quality measures and techniques are specific to the type of deliverables being produced by the project.
- Failure to meet the quality requirements can have negative consequences:
	- Meeting customer requirements by overworking the project team may result in decreased profits and increased levels of overall project risks, employee attrition, errors, or rework.
	- Meeting project schedule objectives by rushing planned quality inspections may result in undetected errors, decreased profits, and increased post-implementation risks.
- The project manager and team are responsible for managing trade-offs associated with delivering the required levels of both **quality** and **grade**.
	- **Quality** is “the degree to which a set of inherent characteristics fulfills requirements” (ISO 9000).
	- **Grade** is a category assigned to deliverables having the same functional use but different technical characteristics. 
- While a quality level that fails to meet quality requirements is always a problem, a low-grade product may not be a problem.
	- It may not be a problem if a suitable low-grade product (one with a limited number of features) is of high quality (no obvious defects). In this example, the product would be appropriate for its general purpose of use.
	- It may be a problem if a high-grade product (one with numerous features) is of low quality (many defects). In essence, a high-grade feature set would prove ineffective and/or inefficient due to low quality.
- Prevention is preferred over inspection. It is better to design quality into deliverables, rather than to find quality issues during inspection. The cost of preventing mistakes is generally much less than the cost of correcting mistakes when they are found by inspection or during usage.
- Team may need a working knowledge of statistical control processes to evaluate data contained in the [[8.3 Control Quality]] outputs. The team should know the differences between the following pairs of terms:
	- **Prevention** (keeping errors out of the process) and **inspection** (keeping errors out of the hands of the customer);
	- **Attribute sampling** (the result either conforms or does not conform) and **variable sampling** (the result is rated on a continuous scale that measures the degree of conformity); and
	- **Tolerances** (specified range of acceptable results) and **control limits** (that identify the boundaries of common variation in a statistically stable process or process performance).
- Project managers may need to be familiar with sampling. Attribute sampling (the result either conforms or does not conform) and variable sampling (the result is rated on a continuous scale that measures the degree of conformity).
- Many projects establish tolerances and control limits for project and product measurements. Tolerances (the specified range of acceptable results) and control limits (the boundaries of common variation in a statistically stable process or process performance).
- The cost of quality (COQ) includes all costs incurred over the life of the product by investment in preventing nonconformance to requirements, appraising the product or service for conformance to requirements, and failing to meet requirements (rework). Cost of quality is often the concern of program management, portfolio management, the PMO, or operations.
- 5 levels of increasingly effective quality management:
	- The most expensive approach is to let the customer find the defects. This approach can lead to warranty issues, recalls, loss of reputation, and rework costs.
	- Detect and correct the defects before the deliverables are sent to the customer as part of the quality control process. The [[8.3 Control Quality]] process has related costs, which are mainly the appraisal costs and internal failure costs.
	- Use quality assurance to examine and correct the process itself and not just special defects.
	- Incorporate quality into the planning and designing of the project and product.
	- Create a culture throughout the organization that is aware and committed to quality in processes and products.

# Trends and Emerging Practices
- **Customer satisfaction**. Understand, evaluate, define, and manage requirements so that customer expectations are met. This requires a combination of conformance to requirements (to ensure the project produces what it was created to produce) and fitness for use (the product or service needs to satisfy the real needs). In agile environments, stakeholder engagement with the team ensures customer satisfaction is maintained throughout the project.
- **Continual improvement**. The plan-do-check-act (PDCA) cycle is the basis for quality improvement as defined by Shewhart and modified by Deming. In addition, quality improvement initiatives such as [[total quality management]] (TQM), [[Six Sigma]], and [[Lean Six Sigma]] may improve both the quality of project management, as well as the quality of the end product, service, or result.
- **Management responsibility**. Success requires the participation of all members of the project team. Management retains, within its responsibility for quality, a related responsibility to provide suitable resources at adequate capacities.
- **Mutually beneficial partnership with suppliers**. Relationships based on partnership and cooperation with the supplier are more beneficial to the organization and to the suppliers than traditional supplier management. The organization should prefer long-term relationships over short-term gains. A mutually beneficial relationship enhances the ability for both the organization and the suppliers to create value for each other, enhances the joint responses to customer needs and expectations, and optimizes costs and resources.
# Tailoring Considerations
| Aspect | Useful Questions |
| ---- | ---- |
| Policy compliance and auditing | - What quality policies and procedures exist in the organization?<br>- What quality tools, techniques, and templates are used in the organization? |
| Standards and regulatory compliance | - Are there any specific quality standards in the industry that need to be applied?<br>- Are there any specific governmental, legal, or regulatory constraints that need to be taken into consideration? |
| Continuous improvement | - How will quality improvement be managed in the project?<br>- Is it managed at the organizational level or at the level of each project? |
| Stakeholder engagement | Is there a collaborative environment with stakeholders and suppliers? |
# In Agile/Adaptive Environments
In order to navigate changes, agile methods call for frequent quality and review steps built in throughout the project rather than toward the end of the project.

Recurring [[Retrospective]]s regularly check on the effectiveness of the quality processes. They look for the [[Root Cause Analysis|root cause]] of issues then suggest trials of new approaches to improve quality. Subsequent retrospectives evaluate any trial processes to determine if they are working and should be continued or new adjusting or should be dropped from use.

In order to facilitate frequent, incremental delivery, agile methods focus on small batches of work, incorporating as many elements of project [[Deliverables]] as possible. Small batch systems aim to uncover inconsistencies and quality issues earlier in the project life cycle when the overall costs of change are lower.