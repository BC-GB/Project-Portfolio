# Project Portfolio
I built these tools to manage different aspects of my daily life with less friction and more effectiveness. Each write-up pairs screenshots with a brief explanation of the problem, the reasoning behind the solution and what the tool enables.

## Investment Research Tool

*Ongoing development of a personal investment-research tool for market analysis, security screening and portfolio management.*

<!-- Add the polished Investment Research Tool screenshot here. -->
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/634062ae-01d3-4c4a-baff-ee8c1eb67e19" />

### The need

Conducting investment research means regularly reviewing and analysing a broad range of market indicators.

### The gap

In practice, preparing the necessary data each time required the repetitive process of sourcing data from numerous websites, cleaning it, rerunning calculations and rebuilding visualisations. As someone busy with academic commitments, the tedious and time-consuming workflow limited how often I could conduct the analysis, the breadth of indicators I could cover and the time available to interpret the evidence.

### The approach

Identifying the process to be highly repeatable in nature, I automated the recurring data work: APIs retrieve the data, while the tool prepares it, calculates the indicators and generates the visualisations. Raw data and calculated outputs are stored in organised, readable files, allowing external AI with folder access to monitor for specified patterns or scan more broadly for notable changes.

### What it enables

As a result, the data, indicators and visualisations are refreshed automatically, while AI-assisted analysis flags potentially notable changes and patterns.

This shifts my attention from maintaining and continually monitoring the evidence base to deciding what notable changes mean and where deeper investigation is warranted.

## Unified Dashboard

*Built an integrated data system that brings fragmented information from multiple sources into a common view for monitoring priorities and coordinating workflows.*

<!-- Add the polished Unified Dashboard screenshot here. -->
<img width="2560" height="1600" alt="Dashboard" src="https://github.com/user-attachments/assets/caed2e6b-5293-4aa4-8cbc-494288adb7bf" />

### The need

Throughout the day, we often rely on separate websites and apps for different needs: a calendar for commitments, a task app for priorities, news sites for updates and a weather app for forecasts.

### The gap

In practice, staying up to date or making changes meant repeatedly switching between apps and tabs, which was tedious and distracting. Fragmentation also limited visibility by separating information that was useful together. For example, I had to compare appointments with weather forecasts across different apps to see which plans might be affected by rain.

### The approach

That required a single place to view the relevant information at a glance and make routine updates. I met this through data integration: the dashboard retrieves relevant data from the services I use, displays it as widgets in one interface and passes task and calendar changes back to their original apps.

### What it enables

The dashboard now serves as my starting point for reviewing the day and making routine changes. This reduces the attention spent navigating separate tools, leaving more for the priorities and commitments themselves.

## Personal Cash-Flow Forecasting System

*Designed a personal-finance system for cash-flow forecasting and spending planning, combining custom modelling with AI-assisted data capture.*

<img width="1794" height="3066" alt="Interface with Mock Data" src="https://github.com/user-attachments/assets/8d0a6b20-245d-46d0-b56f-ca9bdacd7a49" />

[Video demonstrating transaction categorisation](https://github.com/user-attachments/assets/e3e8c9d2-46d3-40eb-9c73-fe9516de6858)

### The need

Managing personal finances well requires understanding both where money is going and what can be afforded over time. A current bank balance provides neither because it does not reveal spending patterns or account for future income and commitments. With limited income over a multi-year degree, that longer-term visibility was essential for deciding how much could be spent or invested while retaining enough cash for future commitments.

### The gap

The two practical alternatives for forecasting spend each had a limitation. Simple monthly averages are easy to calculate but produce a misleading forecast: they spread recurring expenses evenly rather than reflecting when they fall due and treat one-off purchases as part of ongoing spending. A detailed spreadsheet can account for those differences, but doing so requires every purchase to be entered and categorised manually, making the spreadsheet tedious to keep updated.

### The approach

The two limitations are addressed through a forecasting model and AI-assisted data entry and classification. The model classifies expenses into three types based on their expected behaviour over time: “Fixed OPEX” covers recurring expenses, such as subscriptions and supplements, whose future timing and cost can be estimated; “Variable OPEX” covers everyday spending, such as meals and coffee, whose overall level tends to remain relatively stable; and “CAPEX” covers one-off purchases, such as a laptop or television, that are unlikely to recur within the forecast period. To maintain the expense records, AI parses expense details pasted as plain text into structured data and assigns each expense to the appropriate type. The dashboard then uses the resulting spending data and forecasts to produce expenditure analysis and cash-flow visualisations.

### What it enables

The resulting dashboard shows where money is going and visualises projected cash position and runway over time, including how potential purchases would alter that outlook. It provides this detailed view without tedious data entry.

Together, the expenditure analysis and cash-flow forecast enable me to optimise how limited funds are allocated across current spending, potential purchases and investments while retaining the liquidity required for future commitments.

## Exam Revision Planning Tool

*Built an intuitive, seamless interface for tracking progress and adapting revision plans, with support for optimised revision schedules generated by external AI tools.*

<!-- Add the Exam Revision Planning Tool screenshot here. -->
<img width="2560" height="1600" alt="ExamPrepTool" src="https://github.com/user-attachments/assets/20bb7a8c-c2b9-45d7-b769-3d368d4a2b8b" />

### The need

With limited time to prepare for four exams, I needed to make the most of each study session. A revision plan could help by incorporating strategies such as spaced repetition and progression from smaller exercises to full practice exams. However, generating and maintaining that plan also needed to be efficient so that the planning process did not take time away from revision itself.

### The gap

Creating the schedule manually was time-consuming, especially across multiple subjects. An AI chatbot could generate it much faster, but using that schedule in a typical task app still meant entering each task individually and moving tasks one by one whenever revision ran ahead of or behind schedule.

### The approach

To avoid entering each task individually, I designed the tool to load an entire schedule at once from a template that AI chatbots can fill out. When the schedule needs to change, multiple tasks can be adjusted together with only a few intuitive clicks.

### What it enables

The result is a seamless process for building the initial schedule with AI chatbots, loading it into the tool and adapting the plan as revision unfolds. This shifts my time and attention from creating and managing the schedule towards the revision activities it prioritises.

