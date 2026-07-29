# Project Portfolio

## Investment Research Tool

*Developing an investment-research tool for market analysis, security screening and portfolio management.*
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/634062ae-01d3-4c4a-baff-ee8c1eb67e19" />

<!-- Add the polished Investment Research Tool screenshot here. -->


<!-- Context -->
Conducting investment research means regularly reviewing and analysing a broad range of market indicators.

<!-- Complication -->
In practice, each update required sourcing data from numerous websites, cleaning it, rerunning calculations and rebuilding visualisations. As someone busy with academic commitments, this tedious, time-consuming workflow limited how often I could conduct the analysis, the breadth of indicators I could cover and the time available to interpret the evidence.

<!-- Approach -->
To reduce that burden, I automated the recurring data work: APIs retrieve the data, while the tool prepares it, calculates the indicators and generates the visualisations. Raw data and calculated outputs are stored in organised, readable files, allowing external AI with folder access to monitor for specified patterns or scan more broadly for notable changes.

<!-- Operational outcome -->
As a result, the data, indicators and visualisations are refreshed automatically, while selective notifications flag potentially notable changes and patterns.

<!-- Strategic implication -->
This shifts my attention from maintaining and continually monitoring the evidence base to deciding what notable changes mean and where deeper investigation is warranted.

## Unified Dashboard

*Built an integrated data system that brings fragmented information from multiple sources into a common view for monitoring priorities and coordinating workflows.*

<!-- Add the polished Unified Dashboard screenshot here. -->
<img width="2560" height="1600" alt="Dashboard" src="https://github.com/user-attachments/assets/caed2e6b-5293-4aa4-8cbc-494288adb7bf" />

<!-- Context -->
Throughout the day, we often rely on separate websites and apps for different needs: a calendar for commitments, a task app for priorities, news sites for market updates and a weather app for forecasts.

<!-- Complication -->
In practice, keeping up with them meant opening each one separately just to see what was current. Updating a task or calendar commitment required another visit to its original app.

<!-- Approach -->
To reduce that switching, I connected the services I use to a dashboard that retrieves their relevant information into one interface and passes task and calendar changes back to their original apps.

<!-- Operational outcome -->
The result is a dashboard that displays my priorities, schedule, news and weather together and lets me update tasks and calendar entries from the same interface.

<!-- Strategic implication -->
This reduces the attention required to stay up to date across different websites and apps, leaving more attention for the priorities and commitments themselves.

## Personal Cash-Flow Forecasting System

*Designed a personal-finance system for cash-flow forecasting and spending planning, combining custom modelling with AI-assisted data capture.*

<img width="1794" height="3066" alt="Interface with Mock Data" src="https://github.com/user-attachments/assets/8d0a6b20-245d-46d0-b56f-ca9bdacd7a49" />

[Video demonstrating transaction categorisation](https://github.com/user-attachments/assets/e3e8c9d2-46d3-40eb-9c73-fe9516de6858)

<!-- Context -->
Managing personal finances well requires understanding both where money is going and what can be afforded over time. A current bank balance provides neither because it does not reveal spending patterns or account for future income and commitments. With limited income over a multi-year degree, that longer-term visibility was essential for deciding how much could be spent or invested while retaining enough cash for future commitments.

<!-- Complication -->
The two practical alternatives for forecasting spend each had a limitation. Simple monthly averages are easy to calculate but produce a misleading forecast: they spread recurring expenses evenly rather than reflecting when they fall due and treat one-off purchases as part of ongoing spending. A detailed spreadsheet can account for those differences, but doing so requires every purchase to be entered and categorised manually, making the spreadsheet tedious to keep updated.

<!-- Approach -->
The two limitations are addressed through a forecasting model and AI-assisted data entry and classification. The model classifies expenses into three types based on their expected behaviour over time: “Fixed OPEX” covers recurring expenses, such as subscriptions and supplements, whose future timing and cost can be estimated; “Variable OPEX” covers everyday spending, such as meals and coffee, whose overall level tends to remain relatively stable; and “CAPEX” covers one-off purchases, such as a laptop or television, that are unlikely to recur within the forecast period. To maintain the expense records, AI parses expense details pasted as plain text into structured data and assigns each expense to the appropriate type. The dashboard then uses the resulting spending data and forecasts to produce expenditure analysis and cash-flow visualisations.

<!-- Operational outcome -->
The resulting dashboard shows where money is going and visualises projected cash position and runway over time, including how potential purchases would alter that outlook. It provides this detailed view without tedious data entry.

<!-- Strategic implication -->
Together, the expenditure analysis and cash-flow forecast enable me to optimise how limited funds are allocated across current spending, potential purchases and investments while retaining the liquidity required for future commitments.

## Exam Revision Planning Tool

*Built an intuitive, seamless interface for tracking progress and adapting revision plans, with support for optimised revision schedules generated by external AI tools.*

<!-- Add the Exam Revision Planning Tool screenshot here. -->
<img width="2560" height="1600" alt="ExamPrepTool" src="https://github.com/user-attachments/assets/20bb7a8c-c2b9-45d7-b769-3d368d4a2b8b" />

<!-- Context -->
Preparing for several exams means allocating limited study time to across competing subjects. A useful schedule must apply strategies such as spaced repetition and progression from smaller exercises towards full practice exams, while accounting for available study time and the dates and times of each exam.

<!-- Complication -->
An external AI tool can generate that schedule, but putting it into a general task tool still leaves three administrative tasks: entering the plan item by item, checking individual tasks to understand overall progress and moving tasks one by one when revision runs ahead of or behind schedule.

<!-- Approach -->
I designed the tool around those three stages. A YAML template lets an external AI tool return the complete schedule in a format that can be loaded at once, with no AI built into the tool. A thoughtful, minimal-click interface provides direct completion controls and visible progress. Selected tasks can be moved together, while unfinished work can be carried forward in one action.

<!-- Operational outcome -->
The result is a seamless process for building the initial schedule with external AI, loading it into the tool, tracking progress and adapting the plan as revision unfolds.

<!-- Strategic implication -->
Together, these features make it practical to develop and implement a revision-optimised plan throughout exam preparation without diverting limited study time into managing it.
