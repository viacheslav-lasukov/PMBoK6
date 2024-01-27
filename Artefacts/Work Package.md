---
Section: 5.4.3.1
tags:
  - baseline-component
Category: Baseline Component
---
# Description
The lowest level of the [[WBS]] is a work package with a unique identifier. These identifiers provide a structure for hierarchical summation of costs, schedule, and resource information and form a code of accounts. Each work package is part of a control account. A control account is a management control point where scope, budget, and schedule are integrated and compared to the earned value for performance measurement. A control account has two or more work packages, though each work package is associated with a single control account.
# Included In
```dataview
TABLE tags
WHERE contains(file.outlinks, this.file.link)
```
