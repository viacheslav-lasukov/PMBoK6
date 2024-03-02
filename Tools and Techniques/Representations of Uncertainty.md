---
tags:
  - tool-technique
  - topic
Description: "[[Representations of Uncertainty#Description|📝]]"
---
# Description
[[11.4 Perform Quantitative risk analysis|Quantitative Risk Analysis]] requires inputs to a [[Quantitative Risk Analysis Model]] that reflect individual risks and other sources of uncertainty.

Where the duration, cost, or [[Resource]] requirement for a planned activity is uncertain, the range of possible values can be represented in the model as a probability distribution. This may take several forms. The most commonly used are triangular, normal, lognormal, beta, uniform, or discrete distributions. Care should be taken when selecting an appropriate probability distribution to reflect the range of possible values for the planned activity.

[[individual project risk]]s may be covered by probability distributions. Alternatively, risks may be included in the model as probabilistic branches, where optional activities are added to the model to represent the time and/or cost impact of the risk should it occur, and the chance that these activities actually occur in a particular simulation run matches the risk's probability. Branches are most useful for risks that might occur independently of any planned activity. Where risks are related, for example, with a common cause or a logical dependency, correlation is used in the model to indicate this relationship.

Other sources of uncertainty may also be represented using branches to describe alternative paths through the project.