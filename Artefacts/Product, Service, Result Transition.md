---
tags:
  - artefact
Description: Transition of the final product, service, or result that the project was authorized to produce (or in the case of phase closure, the intermediate product, service, or result of that phase) from one team to another.
---
# Description
`=this.Description`
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```