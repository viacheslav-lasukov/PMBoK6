---
tags:
  - "topic"
  - "evm"
  - "tool-technique/data-analysis"
---
# Description
Is used to [[Forecast]] future performance based on past results. It looks ahead in the project for expected slippages and warns the [[Project Manager]] ahead of time that there may be problems later in the schedule if established trends persist. This [[Information]] is made available early enough in the project timeline to give the [[Team]] time to analyze and correct any anomalies. The results of [[trend analysis]] can be used to recommend preventive actions if necessary.

Graphical analysis techniques are valuable for understanding performance to date and for comparison to future performance goals in the form of [[Budget at Completion|BAC]] versus [[Estimate at Completion|EAC]] and completion dates.

EACs are typically based on the [[Actual Cost|AC]]s incurred for work completed, plus an [[Estimate to Complete|ETC]] the remaining work. It is incumbent on the project team to predict what it may encounter to perform the [[Estimate to Complete|ETC]], based on its experience to date. [[Earned Value Analysis|EVA]] works well in conjunction with manual forecasts of the required [[Estimate at Completion|EAC]] costs. The most common [[Estimate at Completion|EAC]] forecasting approach is a manual, bottom-up summation by the [[Project Manager]] and [[Team]].

The [[Project Manager]]'s bottom-up [[Estimate at Completion|EAC]] method builds upon the [[Actual Cost|AC]]s and experience incurred for the work completed, and requires a new [[Estimate]] to complete the remaining project work. Equation: $EAC = AC + bottomupETC$.

The project manager's manual [[Estimate at Completion|EAC]] is quickly compared with a range of calculated [[Estimate at Completion|EAC]]s representing various risk scenarios. When calculating [[Estimate at Completion|EAC]] values, the cumulative [[Cost Performance Index|CPI]] and [[Schedule Performance Index|SPI]] values are typically used.
## [[Estimate at Completion|EAC]] Most Common Methods
| Method | Description | Equation |
| ---- | ---- | ---- |
| [[Estimate at Completion]] [[Forecast]] for [[Estimate to Complete]] work performed at the budgeted rate | Accepts the actual project performance to date (whether favorable or unfavorable) as represented by the [[Actual Cost]]s, and predicts that all future [[Estimate to Complete]] work will be accomplished at the budgeted rate. When actual performance is unfavorable, the [[assumption]] that future performance will improve should be accepted only when supported by project risk analysis | $EAC = AC + (BAC – EV)$ |
| [[Estimate at Completion]] [[Forecast]] for [[Estimate to Complete]] work performed at the present [[Cost Performance Index]] | Assumes that what the project has experienced to date can be expected to continue in the future. The [[Estimate to Complete]] work is assumed to be performed at the same cumulative [[Cost Performance Index]] as that incurred by the project to date | $EAC = BAC / CPI$ |
| [[Estimate at Completion]] [[Forecast]] for [[Estimate to Complete]] work considering both [[Schedule Performance Index]]and [[Cost Performance Index]] factors | The [[Estimate to Complete]] work will be performed at an efficiency rate that considers both the cost and schedule performance indices. This method is most useful when the project schedule is a factor impacting the [[Estimate to Complete]] effort. [[Variation]]s of this method weight the [[Cost Performance Index]] and [[Schedule Performance Index]]at different values (e.g., 80/20, 50/50, or some other ratio) according to the project manager's judgment | $EAC = AC + (BAC – EV) / (CPI × SPI)$ |
## Examples
### Charts
In [[Earned Value|EV]] analysis, three parameters of [[Planned Value|PV]], [[Earned Value|EV]], and [[Actual Cost|AC]] can be monitored and reported on both a period-by-period basis (typically weekly or monthly) and on a cumulative basis. Example shows S-curves to display EV [[Data]] for a project that is performing over [[Budget]] and behind the schedule. ![[Earned Value, Planned Value, and Actual Costs.png]]
### Forecasting
As the project progresses, the [[Team]] may develop a [[Forecast]] for the [[Estimate]] at completion (EAC) that may differ from the [[Budget at Completion|BAC]] (BAC) based on the project performance. If it becomes obvious that the BAC is no longer viable, the [[Project Manager]] should consider the forecasted EAC. Forecasting the EAC involves making projections of conditions and events in the project's future based on current performance [[Information]] and other [[Knowledge]] available at the time of the forecast. Forecasts are generated, updated, and reissued based on [[Work Performance Data]] that is provided as the project is executed. The [[Work Performance Information]] covers the project's past performance and any [[Information]] that could impact the project in the future.
