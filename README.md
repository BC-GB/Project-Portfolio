# Benedict's Project Portfolio

---

## Projects

### 1. Personal Cash-Flow Forecasting System

**Screenshots & demo**  
![Interface with mock data](https://github.com/user-attachments/assets/8ee11582-0daa-42fc-8fad-d681cd270377)  
[Video demonstrating transaction categorisation](https://github.com/user-attachments/assets/e3e8c9d2-46d3-40eb-9c73-fe9516de6858)

#### Context & Importance
Effective budgeting and spending controls are fundamental to financial responsibility. As a university student with limited income streams, I required accurate, granular visibility into my cash flow to maintain a stable financial runway across my multi-year degree.

#### The Gap
Traditional forecasting relies on simple monthly averages, which are inherently unreliable given that purchases are often irregular or regular but over larger timeframes.

While spreadsheets can bridge this forecasting gap and track hidden expenses like annual subscriptions, they are far too tedious to maintain manually.

#### Approach
I designed a framework where spending was decomposed into three mutually exclusive types: **Recurring** (fixed, scheduled bills), **Capital** (one-off, large purchases), or **General run-rate** (variable, day-to-day spending). 

By splitting expenses this way, I could apply the right forecasting logic to each. For example, isolating both large capital purchases and scheduled recurring bills prevents them from distorting the run-rate average.

To reduce manual data entry, I integrated AI into the interface to parse unstructured raw text into structured data (such as name, price, and type)

#### Outcomes & Impact
By separating my expenses into these three distinct streams, I generated a reliable forecasting model that provided comprehensive visibility into my financial health. It allowed me to accurately project my runway, anticipate future cashflow needs, actively manage liquidity, and identify underlying spending patterns.

Crucially, because this approach cleanly centralised my spending data, the tool naturally evolved into an extensible platform. With the underlying data already consolidated, it became simple to build and integrate adjacent features such as inventory tracking, scenario simulations, and automated shopping lists.

**Built with:** TypeScript, React, Python/FastAPI, SQLite

---

### 2. Automated Stock Idea Screener

**Screenshot**  
<img width="1920" height="1080" alt="Stock Screener Dashboard" src="https://github.com/user-attachments/assets/3442eee0-b2a9-4529-96bf-eef893b02b6e" />

#### Context & Importance
Evaluating stock ideas effectively requires pulling together disparate financial data to compare metrics side-by-side, a process that forms the foundation of any sound investment hypothesis.

#### The Gap
The manual grind of jumping between websites and copying data into Excel each session was heavily time-consuming and limited the volume of ideas I could realistically track and compare.

#### Approach
I built a lightweight Python tool that automated API data retrieval directly into an Excel calculation sheet. This sheet handled formulas, historical lookups, and custom metrics, feeding clean outputs directly into a dashboard for side-by-side comparison.

I deliberately kept the spreadsheet as the transparent "engine," making it easy to audit and extend the underlying logic, trading off broad scalability for a highly tailored, focused watchlist experience.

#### Outcomes & Impact
Removed hours of searching up financial sites and manual data entry per session, allowing me to focus entirely on analysis and comparison rather than data gathering. 

**Built with:** Python, xlwings (Excel automation)

---

### 3. Exam Revision & Progress Tracker

**Screenshot**  
<img width="1920" height="1080" alt="Exam Study Tracker" src="https://github.com/user-attachments/assets/82d47faa-813b-495d-b9ba-b8a921851006" />

#### Context & Importance
Preparing for several exams simultaneously requires translating a massive volume of unstructured course materials such as practice exams, tutorial questions, and quizzes into a concrete, actionable daily schedule.

#### The Gap
Standard productivity tools introduce immense friction at two critical stages. First, the manual data entry required to generate a comprehensive study plan from raw course materials is highly time-consuming. Second, as actual progress inevitably deviates from the initial ideal plan, the administrative burden of manually shifting dozens of tasks causes standard systems to become unwieldy and quickly abandoned.

#### Approach
I focused the design on two core elements to eliminate the friction of planning and constant replanning:

First, I utilised structured data by storing the schedule as a plain YAML file. This format enabled me to leverage AI directly. By simply feeding in raw text the list of practice materials, alongside exam dates and priorities, I could instantly generate a comprehensive YAML study plan. This made initial planning exceptionally fast and avoided the need to build complex scheduling logic myself.

Second, I built an incredibly seamless interface to ensure updating those plans was quick and easy. Featuring drag-and-drop rescheduling and real-time progress tracking, it allowed me to effortlessly readjust the schedule on the fly to reflect the actual pace of my revision.
#### Outcomes & Impact
By completely removing the administrative overhead of building and maintaining a schedule, planning and replanning dropped from an hours-long manual chore to a process of minutes. This kept me perfectly synchronised with shifting priorities and allowed me to retain total focus on actual studying, rather than managing the plan itself.

**Built with:** JavaScript, Python, HTML/CSS

---

### 4. AI File Sorter

#### Context & Importance
Folders, especially downloads directories, are frequently full of files with unhelpful names. Sorting and renaming these files into appropriate folders is vital for cleaning up, ensuring proper record keeping, and maintaining accessibility.

#### The Gap
Sorting and renaming files manually are incredibly tedious processes. Because of this high friction, files naturally accumulate in a disorganised state.

#### Approach
While previously a near impossible task to automate reliably, generative AI now makes this achievable. I built a tool where AI reads the actual contents of each file to intelligently rename and sort them into appropriate folders.

The system features a feedback loop that updates its assumptions about folder categories if users manually adjust a file location to correct it. Furthermore, the tool is built fundamentally for security and privacy, featuring the use of local LLMs so that file contents are completely private and never leave the device.

#### Outcomes & Impact
The tool automates the tedious processes of file management. It consistently maintains organised folders and clear file names, ensuring strong accessibility and proper keeping while guaranteeing user privacy through local processing.

**Built with:** Python, Ollama

---

## Contact

**GitHub:** [@BC-GB](https://github.com/BC-GB)

All repositories are private but available for review upon request.
