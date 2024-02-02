---
Description: Any unique and verifiable product, result, or capability to perform a service that is required to be produced to complete a process, phase, or project. Deliverables are typically the outcomes of the project and can include components of the [[Project Management Plan]]. [[Change Control]] should be applied once the first version of a deliverable has been completed. The control of the multiple versions or editions of a deliverable (e.g., documents, software, and building blocks) is supported by configuration management tools and procedures.
tags:
  - artefact
---
# Description
`=this.Description`
# Examples
- Approved product specifications
- Delivery receipts
- Work performance documents
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
