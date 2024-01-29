---
Section: "5.4.3.1"
tags:
  - "baseline-component"
Categories:
  - "Baseline Component"
---
# Description
[[WBS]] component below the [[Control Account]] and above the [[Work Package]] with known work content but without detailed schedule activities.
# Included In
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
```

