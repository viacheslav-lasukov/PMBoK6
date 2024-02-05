---
tags:
  - knowledge-area
page: 129
Learn More:
  - "[[Requirements Management: A Practice Guide]]"
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
	- **Product scope** — the features and functions that characterize a product, service, or result.
	- **Project scope** — the work performed to deliver a product, service, or result with the specified features and functions.
- Project life cycles range along a continuum from predictive to adaptive or agile. In a life cycle that uses a predictive approach, the project deliverables are defined at the beginning of the project and any changes to the scope are progressively managed. In an adaptive or agile approach, the deliverables are developed over multiple iterations where a detailed scope is defined and approved for each iteration when it begins.
	- Projects with adaptive life cycles are intended to respond to high levels of change and require ongoing stakeholder engagement. The overall scope of an adaptive project will be decomposed into a set of requirements and work to be performed, sometimes referred to as a product backlog. At the beginning of an iteration, the team will work to determine how many of the highest-priority items on the backlog list can be delivered within the next iteration. Three processes ([[5.2 Collect Requirements]], [[5.3 Define Scope]], [[5.4 Create WBS]]) are repeated for each iteration. On the contrary, in a predictive project, these processes are performed toward the beginning of the project and updated as necessary, using the integrated change control process.
	- In an adaptive or agile life cycle, the sponsor and customer representatives should be continuously engaged with the project to provide feedback on deliverables as they are created and to ensure that the product backlog reflects their current needs. Two processes ([[5.5 Validate Scope]] and [[5.6 Control Scope]]) are repeated for each iteration. On the contrary, in a predictive project, Validate Scope occurs with each deliverable or phase review and Control Scope is an ongoing process.
	- In predictive projects, the [[Scope Baseline]] for the project is the approved version of the [[Project Scope Statement]], [[Work Breakdown Structure]], and its associated [[WBS Dictionary]]. A baseline can be changed only through formal [[Change Control Procedures]] and is used as a basis for comparison while performing [[5.5 Validate Scope]] and [[5.6 Control Scope]] processes as well as other controlling processes. Projects with adaptive life cycles use backlogs (including product requirements and user stories) to reflect their current needs.
- Completion of the **project** scope is measured against the **project management plan**. Completion of the **product** scope is measured against the **product requirements**.
	- **Requirement** — condition or capability that is required to be present in a product, service, or result to satisfy an agreement or other formally imposed specification.

# Trends and Emerging Practices
- Activities of business analysis may start before a project is initiated and a project manager is assigned. According to [[Requirements Management: A Practice Guide]], the requirements management process starts with a needs assessment, which may begin in portfolio planning, in program planning, or within a discrete project.
- Focus on collaborating with business analysis professionals to:
	- Determine problems and identify business needs;  
	- Identify and recommend viable solutions for meeting those needs;
	- Elicit, document, and manage stakeholder requirements in order to meet business and project objectives;
	- Facilitate the successful implementation of the product, service, or end result of the program or project.
- The process ends with the requirements closure, which transitions the product, service, or result to the recipient in order to measure, monitor, realize, and sustain benefits over time.
- The role with responsibility to conduct business analysis should be assigned to resources with sufficient business analysis skills and expertise. If a business analyst is assigned to a project, requirement-related activities are the responsibility of that role. The project manager is responsible for ensuring that requirements-related work is accounted for in the project management plan and that requirements-related activities are performed on time and within budget and deliver value.
- The relationship between a project manager and a business analyst should be a collaborative partnership. A project will have a higher likelihood of being successful if project managers and business analysts fully understand each other's roles and responsibilities to successfully achieve project objectives.
# Tailoring Considerations
| Aspect | Useful Questions |
| ---- | ---- |
| Knowledge and requirements management | - Does the organization have formal or informal knowledge and requirements management systems?<br>- What guidelines should the project manager establish for requirements to be reused in the future? |
| Validation and control | - Does the organization have existing formal or informal validation and control-related policies, procedures, and guidelines? |
| Use of agile approach | - Does the organization use agile approaches in managing projects? Is the development approach iterative or incremental? Is a predictive approach used? Will a hybrid approach be productive? |
| Governance | - Does the organization have formal or informal audit and governance policies, procedures, and guidelines? |
# In Agile/Adaptive Environments
In projects with evolving requirements, high risk, or significant uncertainty, the scope is often not understood at the beginning of the project or it evolves during the project. Agile methods deliberately spend less time trying to define and agree on scope in the early stage of the project and spend more time establishing the process for its ongoing discovery and refinement. Many environments with emerging requirements find that there is often a gap between the real business requirements and the business requirements that were originally stated. Therefore, agile methods purposefully build and review prototypes and release versions in order to refine the requirements. As a result, scope is defined and redefined throughout the project. In agile approaches, the requirements constitute the backlog.