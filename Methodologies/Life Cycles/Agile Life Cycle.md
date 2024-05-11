---
tags:
  - "life-cycle"
aliases:
  - "agile"
Requirements: "Dynamic"
Activities: "Repeated until correct"
Delivery: "Frequent small deliveries"
Goal: "Customer value via frequent deliveries and feedback"
---
# #agile-practice-guide 
Leverage both the aspects of [[Iterative Life Cycle|iterative]] and [[Incremental Life Cycle|incremental]] characteristics. When [[Team|team]]s use agile approaches, they iterate over the product to create finished [[Deliverables]]. The [[Team|team]] gains early feedback and provides [[Customer]] visibility, confidence, and [[control]] of the [[product]]. Because [[Team|team]] can release earlier, the [[Project|project]] may provide an earlier ROI because the [[Team|team]] delivers the highest [[Value]] work first.
![[Iteration-Based and Flow-Based Agile Life Cycles.png]]
## Agile Manifesto
- **Individuals and interactions** over processes and tools
- **Working software** over comprehensive documentaiton
- **Customer collaboration** over contract negotiation
- **Responding to change** over following a plan
## Principles
- Our highest priority is to satisfy the [[Customer]] through the early and continuous delivery of valuable software.
- Working software is the primary measure of progress.
- Welcome changing requirements, even late in development. Agile processes harness change for the customer’s competitive advantage.
- Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.
- Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.
- Continuous attention to technical excellence and good design enhances agility.
- Business people and developers must work together daily throughout the [[project]].
- Simplicity–the art of maximizing the amount of work not done–is essential.
- Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
- The best architectures, requirements, and designs emerge from self-organizing teams.
- The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.
- At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.
## Relationship Between Values, Principles, and Common Practices
![[The Relationship Between Agile Manifesto Values, Principles, and Common Practices.png]]
## Other Approaches
![[Agile is a Blanket Term for Many Approaches.png]]
## Uncertainty
![[Uncertainty and Complexity Model Inspired by the Stacey Complexity Model.png]]
## Agile Roles
| Role                             | Description |
| -------------------------------- | ----------- |
| Cross-functional [[Team]] member |             |
| [[Product Owner]]                |             |
| Team Facilitator                 |             |
## Agile Practices
- [[Retrospective]]
- [[Backlog]] preparation
- [[Backlog Refinement]]
- [[Daily Standup]]
- [[Demonstration]]
- [[Iteration Planning]]
### Additional Practices
- [[Continuous Integration]]
- Test at all levels
	- [[Unit Testing]] should be done for the building blocks
	- [[System-level testing]] should be done to make sure that the building blocks are communicating data properly
	- [[Smoke Testing]] is comprised of a set of tests that aim at ensuring that the most important functions work. The result of this testing is used to decide if a build is stable enough to proceed with further testing.
	- After [[Smoke Testing]], [[regression testing]] is done.  [[Regression testing]] is when you are testing around specific areas of an application where [[defect]]s have been fixed to ensure that no other issues have been introduced.
	- [[Agile team]]s have a strong preference for [[automated test]]s that ensure uniformity of testing through the design-test-deliver cycle (see [[Acceptance Test-Driven Development|ATDD]]).
- [[Acceptance Test-Driven Development]]
- [[Test-Driven Development]] and [[Behaviour-Driven Development]]
- [[Spike]]s
## Measurements
- [[Burndown Chart]]
- [[Kanban Board]]
- [[Product Backlog Burnup Chart]]
- [[Cumulative Flow Diagram]]
- [[Earned Value Analysis|EVA]] ![[EV in an Agile Context.png]]
## Role of [[Project Management Office|PMO]] in Agile
An Agile [[Project Management Office|PMO]] is:
- Value-driven
- Invitation-oriented. Incorporate the desire for employee engagement by inviting only those interested to engage with [[Project Management Office|PMO]] services.
- Multidisciplinary:
	- Developing and implementing standards
	- Developing personnel through training and mentoring
	- Multiproject management
	- Facilitating [[organizational learning]]
	- Managing [[stakeholders]]
	- Recruiting, selecting, and evaluating team leaders
	- Executing specialized tasts for [[project]]s
## Application of #agile in #pmbok6/knowledge-area s
| #pmbok6/knowledge-area | Application in an Agile Work Process |
| ---- | ---- |
| [[4 Integration Management]] | [[Iterative Life Cycle\|iterative]] and [[Agile Life Cycle\|agile]] approaches promote the engagement of [[Team]] members as local domain experts in integration management. The team members determine how plans and components should integrate.<br><br>The expectations of the [[Project Manager]]as noted in the [[4 Integration Management#Key Concepts\|Key Concepts]] do not change in an [[Adaptive Life Cycle\|Adaptive]] environment, but control of the detailed product planning and delivery is delegated to the [[Team]]. The [[Project Manager]]’s focus is on building a collaborative [[Decision Making]] environment and ensuring the [[Team]] has the ability to respond to changes. This collaborative approach can be further enhanced when team members possess a broad skill base rather than a narrow specialization. |
| [[5 Scope Management]] | In projects with evolving requirements, high risk, or significant uncertainty, the scope is often not understood at the beginning of the project or it evolves during the project. Agile methods deliberately spend less time trying to define and agree on scope in the early stage of the project and spend more time establishing the process for its ongoing discovery and refinement. Many environments with emerging requirements find that there is often a gap between the real business requirements and the business requirements that were originally stated. Therefore, agile methods purposefully build and review prototypes and release versions in order to refine the requirements. As a result, scope is dened and redened throughout the project. In agile approaches, the requirements constitute the backlog. |
| [[6 Schedule Management]] | Adaptive approaches use short cycles to undertake work, review the results, and adapt as necessary. These cycles provide rapid feedback on the approaches and suitability of deliverables, and generally manifest as iterative scheduling and on-demand, pull-based scheduling, as discussed in the [[6 Schedule Management#Trends and Emerging Practices\|Trends and Emerging Practices]].<br><br>In large organizations, there may be a mixture of small projects and large initiatives requiring long-term roadmaps to manage the development of these programs using scaling factors (e.g., team size, geographical distribution, regulatory compliance, organizational complexity, and technical complexity). To address the full delivery life cycle for larger, enterprise-wide systems, a range of techniques utilizing a predictive approach, adaptive approach, or a hybrid of both, may need to be adopted. The organization may need to combine practices from several core methods, or adopt a method that has already done so, and adopt a few principles and practices of more traditional techniques.<br><br>The role of the [[Project Manager]] does not change based on managing projects using a [[Predictive Life Cycle\|Predictive]] development life cycle or managing projects in [[Adaptive Life Cycle\|Adaptive]] environments. However, to be successful in using [[Adaptive Life Cycle\|Adaptive]] approaches, the project manager will need to be familiar with the #tool-technique s to understand how to apply them effectively. |
| [[7 Cost Management]] | Projects with high degrees of uncertainty or those where the scope is not yet fully defined may not benefit from detailed cost calculations due to frequent changes. Instead, lightweight estimation methods can be used to generate a fast, high-level forecast of project labor costs, which can then be easily adjusted as changes arise. Detailed estimates are reserved for short-term planning horizons in a just-in-time fashion.<br><br>In cases where high-variability projects are also subject to strict budgets, the scope and schedule are more often adjusted to stay within cost constraints. |
| [[8 Quality Management]] | In order to navigate changes, agile methods call for frequent quality and review steps built in throughout the project rather than toward the end of the project.<br><br>Recurring [[retrospective]]s regularly check on the effectiveness of the quality processes. They look for the root cause of issues then suggest trials of new approaches to improve quality. Subsequent retrospectives evaluate any trial processes to determine if they are working and should be continued or new adjusting or should be dropped from use.<br><br>In order to facilitate frequent, incremental delivery, agile methods focus on small batches of work, incorporating as many elements of project deliverables as possible. Small batch systems aim to uncover inconsistencies and quality issues earlier in the project life cycle when the overall costs of change are lower. |
| [[9 Resource Management]] | Projects with high variability benefit from [[Team]] structures that maximize focus and collaboration, such as self-organizing teams with generalizing specialists. Collaboration is intended to boost productivity and facilitate innovative problem solving. Collaborative teams may facilitate accelerated integration of distinct work activities, improve communication, increase knowledge sharing, and provide  exibility of work assignments in addition to other advantages.<br><br>Although the benefits of collaboration also apply to other project environments, collaborative teams are often critical to the success of projects with a high degree of variability and rapid changes, because there is less time for centralized tasking and decision making.<br><br>Planning for physical and human resources is much less predictable in projects with high variability. In these environments, agreements for fast supply and lean methods are critical to controlling costs and achieving the schedule. |
| [[10 Communications Management]] | Project environments subject to various elements of ambiguity and change have an inherent need to communicate evolving and emerging details more frequently and quickly. This motivates streamlining team member access to information, frequent team checkpoints, and colocating team members as much as possible.<br><br>In addition, posting project artifacts in a transparent fashion, and holding regular stakeholder reviews are intended to promote communication with management and stakeholders. |
| [[11 Risk Management]] | High-variability environments, by definition, incur more uncertainty and risk. To address this, projects managed using adaptive approaches make use of frequent reviews of incremental work products and cross-functional project teams to accelerate knowledge sharing and ensure that risk is understood and managed. Risk is considered when selecting the content of each iteration, and risks will also be identified, analyzed, and managed during each iteration.<br><br>Additionally, the requirements are kept as a living document that is updated regularly, and work may be reprioritized as the project progresses, based on an improved understanding of current risk exposure. |
| [[12 Procurement Management]] | In agile environments, specic sellers may be used to extend the team. This collaborative working relationship can lead to a shared risk procurement model where both the buyer and the seller share in the risk and rewards associated with a project.<br><br>Larger projects may use an adaptive approach for some deliverables and a more stable approach for other parts. In these cases, a governing agreement such as a master services agreement (MSA) may be used for the overall engagement, with the adaptive work being placed in an appendix or supplement. This allows changes to occur on the adaptive scope without impacting the overall contract. |
| [[13 Stakeholder Management]] | Projects experiencing a high degree of change require active engagement and participation with project stakeholders. To facilitate timely, productive discussion and decision making, adaptive teams engage with stakeholders directly rather than going through layers of management. Often the client, user, and developer exchange information in a dynamic co-creative process that leads to more stakeholder involvement and higher satisfaction. Regular interactions with the stakeholder community throughout the project mitigate risk, build trust, and support adjustments earlier in the project cycle, thus reducing costs and increasing the likelihood of success for the project.<br><br>In order to accelerate the sharing of information within and across the organization, agile methods promote aggressive transparency. The intent of inviting any stakeholders to project meetings and reviews or posting project artifacts in public spaces is to surface as quickly as possible any misalignment, dependency, or other issue related to the changing project. |
