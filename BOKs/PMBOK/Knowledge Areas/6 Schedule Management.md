---
tags:
  - pmbok6/knowledge-area
page: 173
Learn More:
  - "[[Practice Standard for Scheduling]]"
---
# Processes
```dataview
LIST
FROM #pmbok6/process 
WHERE KnowledgeArea=link(this.file.name)
SORT file.name
```
# Key Concepts
- Project scheduling provides a detailed plan that represents how and when the project will deliver the [[Products, Services, Results]] defined in the project scope and serves as a tool for communication, managing stakeholders’ expectations, and as a basis for performance reporting.
- The [[Project Management Team]] selects a scheduling method, such as [[Critical Path]] or an [[Agile Life Cycle|agile]] approach. Then, the project-specific data, such as the activities, planned dates, durations, [[Resource]]s, dependencies, and constraints, are entered into a [[Scheduling Tool]] to create a [[Schedule Model]] for the project. The result is a [[project schedule]].
- The [[project schedule]] is used as a tool for communication, managing stakeholder expectations, and a basis for performance reporting.
- When possible, the detailed [[project schedule]] should remain flexible throughout the project to adjust for [[Knowledge]] gained, increased understanding of the risk, and value-added activities.
# Trends and Emerging Practices
- **Alterative scheduling with a backlog**. [[Requirement]]s are documented in [[User Story|User Stories]] that are then prioritized and refined just prior to construction, and the features are developed using time-boxed periods of work. This approach is often used to deliver incremental value to the [[Customer]] or when multiple [[Team]]s can concurrently develop a large number of features that have few interconnected dependencies. It welcomes changes throughout the development life cycle.
- **On-demand scheduling**. Typically used in a [[Kanban]] system. It is based on the [[Theory of Constraints]] and [[Pull-based Scheduling]] concepts from [[Lean]] manufacturing to limit a team's [[Work in Progress]] in order to balance demand against the [[Team]]'s delivery throughput. On-demand #scheduling does not rely on a schedule that was developed previously for the development of the [[Product]] or [[increment]]s, but rather pulls work from a backlog or intermediate queue of work to be done immediately as [[Resource]]s become available. On-demand scheduling is often used for projects that evolve the [[Product]] [[Incremental Life Cycle|incremental]]ly in [[Operation]]al or sustainment environments, and where tasks may be made relatively similar in size and [[Scope]] or can be bundled by size and [[Scope]].
# [[Tailoring]] Considerations
| Aspect | Useful Questions |
| ---- | ---- |
| Life cycle approach | - What is the most appropriate life cycle approach that allows for a detailed schedule? |
| Duration and [[Resource]] | - What are the factors influencing durations, such as the correlation between [[Resource]] availability and productivity? |
| Project dimensions | - How will the presence of [[Project]] complexity, technological uncertainty, [[Product]] novelty, pace or progress tracking, (such as [[Earned Value Analysis\|EVA]], percentage complete, red-yellow-green (stop light) indicators) impact the desired level of control? |
| Technology support | - Is technology used to develop, record, transmit, receive, and store project [[Schedule Model]] [[Information]] and is it readily accessible? |
# In [[Agile Life Cycle|Agile]] Environments
Use short cycles to undertake work, review the results, and adapt as necessary. These cycles provide rapid feedback on the approaches and suitability of deliverables, and generally manifest as iterative scheduling and on-demand, [[Pull-based Scheduling]].
In large organizations, there may be a mixture of small projects and large [[initiative]]s requiring long-term roadmaps to manage the development of these programs using scaling factors (e.g., team size, [[Geographic Distribution of Facilities and Resources]], [[Laws, Legislation, Regulations and Compliance Requirements]], organizational complexity, and technical complexity). To address the full delivery [[Project Life Cycle|life cycle]] for larger, enterprise-wide systems, a range of techniques utilizing a [[Predictive Life Cycle|predictive]] approach, [[Adaptive Life Cycle|Adaptive]] approach, or a [[Hybrid Life Cycle|hybrid]] of both, may need to be adopted. The [[Organization]] may need to combine practices from several core methods, or adopt a method that has already done so, and adopt a few principles and practices of more traditional techniques.