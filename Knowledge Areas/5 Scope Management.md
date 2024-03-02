---
tags:
  - pmbok6/knowledge-area
page: 129
Learn More:
  - "[[Requirements Management. A Practice Guide]]"
  - "[[Business Analysis for Practitioners. A Practice Guide]]"
---
# Processes
```dataview
LIST
FROM #process 
WHERE KnowledgeArea=link(this.file.name)
SORT name
```
# Key Concepts
- Scope can refer to:
	- [[Product Scope]]
	- [[Project Scope]]
- [[Project Life Cycle]]s range along a continuum from [[Predictive Life Cycle|predictive]] to adaptive or [[Agile Life Cycle|agile]]. In a life cycle that uses a predictive approach, the [[deliverables]] are defined at the beginning and any [[Change]]s to the [[Scope]] are progressively managed. In an [[Adaptive Life Cycle|Adaptive]] or [[Agile Life Cycle|agile]] approach, the [[deliverables]] are developed over multiple [[iteration]]s where a detailed [[Scope]] is defined and approved for each [[Iteration]] when it begins.
	- Projects with adaptive life cycles are intended to respond to high levels of change and require ongoing stakeholder engagement. The overall [[Scope]] of an [[Adaptive Life Cycle|Adaptive]] [[Project]] will be decomposed into a set of [[requirement]]s and work to be performed, sometimes referred to as a [[product backlog]]. At the beginning of an [[iteration]], the [[Team]] will work to determine how many of the highest-priority items on the [[product backlog|Backlog]] list can be delivered within the next [[iteration]]. Three processes ([[5.2 Collect Requirements]], [[5.3 Define Scope]], [[5.4 Create WBS]]) are repeated for each [[iteration]]. On the contrary, in a [[Predictive Life Cycle|Predictive]] [[Project]], these processes are performed toward the beginning of the [[Project]] and updated as necessary, using the [[4.6 Perform Integrated Change Control]] #pmbok6/process.
	- In an adaptive or [[Agile Life Cycle|agile]] life cycle, the sponsor and [[Customer]] representatives should be continuously engaged with the project to provide feedback on deliverables as they are created and to ensure that the product backlog reflects their current needs. Two processes ([[5.5 Validate Scope]] and [[5.6 Control Scope]]) are repeated for each iteration. On the contrary, in a [[Predictive Life Cycle]] project, [[5.5 Validate Scope]] occurs with each deliverable or phase review and [[5.6 Control Scope]] is an ongoing process.
	- In predictive projects, the [[Scope Baseline]] is the approved version of the [[Project Scope Statement]], [[Work Breakdown Structure]], and its associated [[WBS Dictionary]]. A baseline can be changed only through formal [[Change Control]] and is used as a basis for comparison while performing [[5.5 Validate Scope]] and [[5.6 Control Scope]] processes as well as other controlling processes. Projects with adaptive life cycles use [[product backlog|Backlog]]s (including [[product requirements]] and [[User Story|User Stories]]) to reflect their current [[Need]]s.
- Completion of the [[Project Scope]] is measured against the [[project management plan]]. Completion of the [[Product Scope]] is measured against the [[product requirements]].
	- **Requirement** — condition or capability that is required to be present in a [[Products, Services, Results]] to satisfy an agreement or other formally imposed [[Specification]].
# Trends and Emerging Practices
- Activities of business analysis may start before a project is initiated and a project manager is assigned. According to [[Requirements Management. A Practice Guide]], the requirements management process starts with a needs assessment, which may begin in portfolio planning, in program planning, or within a discrete project.
- Focus on collaborating with business analysis professionals to:
	- Determine problems and identify [[Business Need]]s
	- Identify and recommend viable solutions for meeting [[Business Need]]s
	- Elicit, document, and manage stakeholder requirements in order to meet business and [[Project]] [[Objective]]s
	- Facilitate the successful implementation of the [[Products, Services, Results]] of the [[Program]] or [[Project]]
- The process ends with the [[requirement]]s closure, which transitions the [[Products, Services, Results]] to the recipient in order to measure, monitor, realize, and sustain benefits over time.
- The role with responsibility to conduct [[business analysis]] should be assigned to [[Resource]]s with sufficient [[business analysis]] skills and expertise. If a [[Business Analyst]] is assigned to a [[Project]], [[requirement]]-related [[Activity|Activities]] are the responsibility of that role. The [[Project Manager]] is responsible for ensuring that requirements-related work is accounted for in the [[Project Management Plan]] and that [[requirement]]s-related activities are performed on time and within [[Budget]] and deliver [[value]].
- The relationship between a [[Project Manager]] and a [[Business Analyst]] should be a collaborative partnership. A [[Project]] will have a higher likelihood of being successful if [[Project Manager]]s and [[Business Analyst]]s fully understand each other's [[Roles and Responsibilities]] to successfully achieve [[Objective]]s.
# [[Tailoring]] Considerations
| Aspect | Useful Questions |
| ---- | ---- |
| [[Knowledge Management]] and [[Requirements Management]]  | - Does the [[Organization]] have formal or informal [[Knowledge Management]] and [[Requirements Management]]  systems?<br>- What guidelines should the [[Project Manager]] establish for [[Requirement]]s to be reused in the future? |
| [[Validation]] and [[Control]] | - Does the [[Organization]] have existing formal or informal [[Validation]] and [[Scope-Control Policies, Procedures, Guidelines]]? |
| Use of [[Agile Life Cycle\|agile]] approach | - Does the [[Organization]] use [[Agile Life Cycle\|agile]] approaches in [[Project Management]]? Is the [[development approach]] [[Iterative Life Cycle\|iterative]] or [[Incremental Life Cycle\|incremental]]? Is a [[Predictive Life Cycle\|Predictive]] approach used? Will a [[Hybrid Life Cycle\|hybrid]] approach be productive? |
| Governance | - Does the [[Organization]] have formal or informal [[Audit]] and governance policies, procedures, and guidelines? |
# In [[Agile Life Cycle|Agile]] Environments
In projects with evolving requirements, high risk, or significant uncertainty, the scope is often not understood at the beginning of the project or it evolves during the project. [[Agile Life Cycle|Agile]] methods deliberately spend less time trying to define and agree on scope in the early stage of the project and spend more time establishing the process for its ongoing discovery and refinement. Many environments with emerging requirements find that there is often a gap between the real business requirements and the business requirements that were originally stated. Therefore, [[Agile Life Cycle|agile]] methods purposefully build and review [[prototypes]] and release versions in order to refine the requirements. As a result, scope is defined and redefined throughout the project. In [[Agile Life Cycle|agile]] approaches, the requirements constitute the backlog.