---
tags:
  - "tool-technique"
  - "topic"
  - "evm"
  - "data-analysis"
Description: "[[Trend Analysis#Description|📝]]"
---
# Description
Is used to forecast future performance based on past results. It looks ahead in the project for expected slippages and warns the [[Project Manager]] ahead of time that there may be problems later in the schedule if established trends persist. This information is made available early enough in the project timeline to give the [[project team]] time to analyze and correct any anomalies. The results of [[trend analysis]] can be used to recommend preventive actions if necessary.

Graphical analysis techniques are valuable for understanding performance to date and for comparison to future performance goals in the form of BAC versus estimate at completion (EAC) and completion dates.

EACs are typically based on the [[Actual Cost|AC]]s incurred for work completed, plus an estimate to complete (ETC) the remaining work. It is incumbent on the project team to predict what it may encounter to perform the ETC, based on its experience to date. [[Earned Value Analysis|EVA]] works well in conjunction with manual forecasts of the required [[Estimate at Completion|EAC]] costs. The most common [[Estimate at Completion|EAC]] forecasting approach is a manual, bottom-up summation by the project manager and project team.

The project manager's bottom-up [[Estimate at Completion|EAC]] method builds upon the [[Actual Cost|AC]]s and experience incurred for the work completed, and requires a new estimate to complete the remaining project work. Equation: $[[EAC]] = AC + bottomupETC$.

The project manager's manual [[Estimate at Completion|EAC]] is quickly compared with a range of calculated EACs representing various risk scenarios. When calculating [[Estimate at Completion|EAC]] values, the cumulative [[cost performance index|CPI]] and [[Schedule Performance Index |SPI]]values are typically used.
## [[Estimate at Completion|EAC]] Most Common Methods
| Method | Description | Equation |
| ---- | ---- | ---- |
| [[Estimate at Completion|EAC]] forecast for [[ETC]] work performed at the budgeted rate | Accepts the actual project performance to date (whether favorable or unfavorable) as represented by the [[Actual Cost|AC]]s, and predicts that all future [[ETC]] work will be accomplished at the budgeted rate. When actual performance is unfavorable, the assumption that future performance will improve should be accepted only when supported by project risk analysis | $[[EAC]] = AC + (BAC – EV)$ |
| [[Estimate at Completion|EAC]] forecast for [[ETC]] work performed at the present [[cost performance index|CPI]] | Assumes that what the project has experienced to date can be expected to continue in the future. The [[ETC]] work is assumed to be performed at the same cumulative [[cost performance index]] as that incurred by the project to date | $[[EAC]] = BAC / CPI$ |
| [[Estimate at Completion|EAC]] forecast for [[ETC]] work considering both [[Schedule Performance Index |SPI]]and [[cost performance index|CPI]] factors | The [[ETC]] work will be performed at an efficiency rate that considers both the cost and schedule performance indices. This method is most useful when the project schedule is a factor impacting the [[ETC]] effort. Variations of this method weight the [[cost performance index|CPI]] and [[Schedule Performance Index |SPI]]at different values (e.g., 80/20, 50/50, or some other ratio) according to the project manager's judgment | $[[Estimate at Completion|EAC]] = AC + (BAC – EV) / ([[cost performance index|CPI]] × SPI)$ |
## Examples
### Charts
In [[Earned Value|EV]] analysis, three parameters of [[Planned Value|PV]], [[Earned Value|EV]], and [[Actual Cost|AC]] can be monitored and reported on both a period-by-period basis (typically weekly or monthly) and on a cumulative basis. Example shows S-curves to display EV data for a project that is performing over budget and behind the schedule. ![[Earned Value, Planned Value, and Actual Costs.png]]
### Forecasting
As the project progresses, the [[project team]] may develop a forecast for the estimate at completion (EAC) that may differ from the [[Budget at Completion|BAC]] (BAC) based on the project performance. If it becomes obvious that the BAC is no longer viable, the [[Project Manager]] should consider the forecasted EAC. Forecasting the EAC involves making projections of conditions and events in the project's future based on current performance information and other knowledge available at the time of the forecast. Forecasts are generated, updated, and reissued based on [[Work Performance Data]] that is provided as the project is executed. The [[work performance information]] covers the project's past performance and any information that could impact the project in the future.
