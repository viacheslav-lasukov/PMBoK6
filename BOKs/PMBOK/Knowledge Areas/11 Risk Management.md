---
tags:
  - "pmbok6/knowledge-area"
  - "topic"
page: 395
aliases:
  - "Risk Management"
---
# Processes
```dataview
LIST
FROM #pmbok6/process 
WHERE KnowledgeArea=link(this.file.name)
SORT file.name
```
# Key Concepts
- All projects are risky. Organizations choose to take [[Risk]] in order to create value, while balancing risk and reward.
- Risk exists at two levels within every project:
	- ***[[Individual Project Risk]]*** is an uncertain event or condition that, if it occurs, has a positive or negative effect on one or more project objectives.
	- ***[[Overall Project Risk]]*** is the effect of uncertainty on the project as a whole, arising from all sources of uncertainty including individual risks, representing the exposure of stakeholders to the implications of [[Variation]]s in [[Project Outcome]], both positive and negative.
- Risks will continue to emerge during the lifetime of the project, so [[11 Risk Management|Risk Management]] processes should be conducted iteratively.
- In order to manage [[risk]] effectively on a particular [[project]], the [[team]] needs to know what level of [[Risk Exposure]] is acceptable in pursuit of project objectives. This is defined by measurable [[Risk Threshold]]s that reflect the [[risk appetite]] of the [[organization]] and [[stakeholders]].
# Trends and Emerging Practices
- **Non-event risks**. Most projects focus only on risks that are uncertain future events that may or may not occur. Examples: a key [[Seller]] may go out of business during the project, the [[Customer]] may change the requirement after design is complete, subcontractor may propose enhancements to the standard operating processes. Types of non-event risks:
	- **Variability risk**. Uncertainty exists about some key characteristics of a planned event or activity or decision. Examples:
		- productivity may be above or below target
		- number of errors found during testing may be higher or lower than expected
		- unseasonal weather conditions may occur during the construction phase.
		  Can be addressed using [[Monte Carlo Simulation]] analysis, with the range of [[Variation]] reflected in probability distributions, followed by actions to reduce the spread of possible outcomes.
	- **Ambiguity risk**. Uncertainty exists about what might happen in the future. Areas of the project where imperfect [[Knowledge]] might affect the project's ability to achieve its objectives:
		- elements of the requirement or technical solution
		- future developments in regulatory frameworks
		- inherent systemic complexity in the project
		  Managed by defining those areas where there is a deficit of [[Knowledge]] or understanding, then filling the gap by obtaining expert external input or benchmarking against best practices. Addressed through incremental development, prototyping, or simulation.
- **Project resilience**. These are risks that can only be recognized after they have occurred. Emergent risks can be tackled through developing project resilience. This requires each project to have:
	- Right level of [[Budget]] and schedule [[Contingency]] for emergent [[Risk]]s, in addition to a specific risk [[Budget]] for known risks;
	- Flexible project processes that can cope with emergent risk while maintaining overall direction toward project goals, including strong change management;
	- Empowered project team that has clear objectives and that is trusted to get the job done within agreed-upon limits;
	- Frequent review of early warning signs to identify emergent risks as early as possible;
	- Clear input from stakeholders to clarify areas where the [[Project Scope]] or strategy can be adjusted in response to emergent risks.
- **Integrated risk management**. Projects exist in an organizational context, and they may form part of a program or portfolio. Risk exists at each of these levels, and risks should be owned and managed at the appropriate level. Some risks identified at higher levels will be delegated to the project team for management, and some project risks may be escalated to higher levels if they are best managed outside the project. A coordinated approach to enterprise-wide risk management ensures alignment and coherence in the way risk is managed across all levels. This builds risk efficiency into the structure of programs and portfolios, providing the greatest overall value for a given level of [[Risk Exposure]].
# [[Tailoring]] Considerations
| Aspect               | Useful Questions                                                                                                                                                                                                                                                  |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Project size         | - Does the project's size in terms of budget, duration, scope, or team size require a more detailed approach to risk management?<br>- Or is it small enough to justify a simplified risk process?                                                                 |
| Project complexity   | - Is a robust risk approach demanded by high levels of innovation, new technology, commercial arrangements, interfaces, or external dependencies that increase project complexity?<br>- Or is the project simple enough that a reduced risk process will suffice? |
| Project importance   | - How strategically important is the project?<br>- Is the level of risk increased for this project because it aims to produce breakthrough opportunities, addresses significant blocks to organizational performance, or involves major [[Product]] innovation?   |
| Development approach | Is this a waterfall project where risk processes can be followed sequentially and iteratively, or does the project follow an [[Agile Life Cycle\|agile]] approach where risk is addressed at the start of each iteration as well as during execution?             |
# In [[Agile Life Cycle|Agile]] Environments
- **Frequent reviews of increments** and **cross-functional teams** to accelerate [[Knowledge Sharing]] and ensure that risk is understood and managed.
- Risk is considered when selecting the content of each iteration, and risks will also be identified, analyzed, and managed during each iteration.
- Requirements are kept as a living document that is updated regularly.
- Work may be reprioritized as the project progresses, based on an improved understanding of current [[Risk Exposure]].