---
tags:
  - knowledge-area
page: 173
Learn More:
  - "[[Practice Standard for Scheduling]]"
---
# Processes
```dataview
LIST
FROM #process 
WHERE KnowledgeArea=link(this.file.name)
SORT name
```
# Key Concepts
- Project scheduling provides a detailed plan that represents how and when the project will deliver the products, services, and results defined in the project scope and serves as a tool for communication, managing stakeholders’ expectations, and as a basis for performance reporting.
- The project management team selects a scheduling method, such as critical path or an agile approach. Then, the project-specific data, such as the activities, planned dates, durations, resources, dependencies, and constraints, are entered into a scheduling tool to create a schedule model for the project. The result is a project schedule.
- The project schedule is used as a tool for communication, managing stakeholder expectations, and a basis for performance reporting.
- When possible, the detailed project schedule should remain flexible throughout the project to adjust for knowledge gained, increased understanding of the risk, and value-added activities.
# Trends and Emerging Practices
- **Alterative scheduling with a backlog**. Requirements are documented in user stories that are then prioritized and refined just prior to construction, and the product features are developed using time-boxed periods of work. This approach is often used to deliver incremental value to the customer or when multiple teams can concurrently develop a large number of features that have few interconnected dependencies. Benefit — it welcomes changes throughout the development life cycle.
- **On-demand scheduling**. Typically used in a Kanban system. It is based on the theory-of-constraints and [[pull-based scheduling]] concepts from [[Lean]] manufacturing to limit a team's [[work in progress]] in order to balance demand against the team's delivery throughput. On-demand scheduling does not rely on a schedule that was developed previously for the development of the product or product increments, but rather pulls work from a backlog or intermediate queue of work to be done immediately as resources become available. On-demand scheduling is often used for projects that evolve the product incrementally in operational or sustainment environments, and where tasks may be made relatively similar in size and scope or can be bundled by size and scope.
# Tailoring Considerations
| Aspect | Useful Questions |
| ---- | ---- |
| Life cycle approach | - What is the most appropriate life cycle approach that allows for a detailed schedule? |
| Duration and resource | - What are the factors influencing durations, such as the correlation between resource availability and productivity? |
| Project dimensions | - How will the presence of project complexity, technological uncertainty, product novelty, pace or progress tracking, (such as earned value management, percentage complete, red-yellow- green (stop light) indicators) impact the desired level of control? |
| Technology support | - Is technology used to develop, record, transmit, receive, and store project schedule model information and is it readily accessible? |
# In Agile/Adaptive Environments
Use short cycles to undertake work, review the results, and adapt as necessary. These cycles provide rapid feedback on the approaches and suitability of deliverables, and generally manifest as iterative scheduling and on-demand, [[pull-based scheduling]].
In large organizations, there may be a mixture of small projects and large initiatives requiring long-term roadmaps to manage the development of these programs using scaling factors (e.g., team size, geographical distribution, regulatory compliance, organizational complexity, and technical complexity). To address the full delivery life cycle for larger, enterprise-wide systems, a range of techniques utilizing a predictive approach, adaptive approach, or a hybrid of both, may need to be adopted. The organization may need to combine practices from several core methods, or adopt a method that has already done so, and adopt a few principles and practices of more traditional techniques.