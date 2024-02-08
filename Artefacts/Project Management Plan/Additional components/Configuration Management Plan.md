---
tags:
  - "#additional-component"
Description: "[[Configuration Management Plan#Description|📝]]"
---
# Description
Describes how the information about the items of the project (and which items) will be recorded and updated so that the product, service, or result of the project remains consistent and/or operative.
# Included in
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
SORT number(section)
```
