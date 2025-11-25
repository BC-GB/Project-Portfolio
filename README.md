# Benedict's Project Portfolio

> Personal projects where I applied a structured approach to everyday challenges.
> While the use cases are personal, they demonstrate skills such as analytical thinking to solve inefficiencies, eliminate pain points, and design practical and streamlined workflows to gain the tools for better decision-making.
---

## Skills Demonstrated

**Structured Problem-Solving** · **Analytical & Data-Driven Thinking** · **Process & Workflow Design** · **User Experience Design** · **Automation & Efficiency** · **Forecasting & Planning** · **Practical AI Integration**

---

## Projects

### 1. Personal Budgeting & Forecasting



![Screenshot_25-11-2025_23545_localhost](https://github.com/user-attachments/assets/520e24fa-e891-4c74-b2f1-692a3ffe8743)


<div align="center">
  <img src="https://github.com/user-attachments/assets/5195353f-b6eb-4ab6-9445-6dca1b434667" alt="Untitled video - Made with Clipchamp (2)" width="700"/>
  <br/>
  <sub><b>AI feature that transforms raw text into structured data, enabling automated parsing of receipts and shopping carts.</b></sub>
</div>


**Problem**

- Simple “average monthly spend” budgets were misleading due to bulk buying and other long‑cycle purchases.
- I frequently made unnecessary repeat trips to the same stores because I couldn’t see replenishment needs in one place.
- Spreadsheets (even with macros) were clunky for this and don’t behave like a proper relational system.
- I wanted seamlessness such as to minimise manual data entry by pasting raw text and having AI parse it.

**Approach**

- Structured expenses into clear types (e.g. recurring, general, capital‑like) to avoid distorted forecasts.
- Used a relational database to link transactions, categories, and inventory items, with cascading behaviour when records change or are removed.
- Built a simple interface focused on: future cash flow, upcoming commitments, and replenishment needs.
- Integrated AI parsing into the workflow so statements/notes can be turned into structured records with minimal typing.

**Impact**

- **Seamless decision‑making:** Easy to review spending decisions, upcoming obligations, and restock needs without relying on memory.
- **Less mental overhead:** The system tracks details so I don’t have to, freeing attention for actual choices rather than bookkeeping.
- **Future‑proofed for analytics:** The structured, relational design makes it straightforward to add more advanced AI‑driven insights later (e.g. scenario analysis, recommendations), not just text parsing.

**Tech**

TypeScript, React, Python, FastAPI, SQLite

---

### 2. Screener‑Tracker

<img width="1920" height="1080" alt="Stock Screener Dashboard" src="https://github.com/user-attachments/assets/3442eee0-b2a9-4529-96bf-eef893b02b6e" />

**Problem**

- Analysing stocks meant tediously visiting multiple sources and manually copying data into spreadsheets.
- Reliance on manual updates rendered analysis obsolete from one trading session to the next.

**Approach**

- Automated data retrieval from APIs into a spreadsheet using an integration library instead of manual copy‑paste.
- Let the spreadsheet act as the calculation engine (formulas, historical data functions, custom metrics).
- Fed the calculated outputs back into a focused dashboard so I could track and compare ideas without living inside raw sheets.

**Impact**

- **Up‑to‑date analysis:** Automation makes it realistic to refresh views frequently, not just occasionally.
- **Less mechanical work:** Time spent moving and re‑formatting data is replaced by time spent interpreting results.
- **More consistent evaluation:** Each idea is assessed in a structured manner, reducing ad‑hoc judgement.

**Tech**

Python, Excel (via xlwings and built‑in functions)

---

### 3. Exam Study Tracker

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/82d47faa-813b-495d-b9ba-b8a921851006" />

**Problem**

- For multiple exams, I needed to maximise retention and complete all practice within the time available.
- Traditional apps and earlier strategies (e.g. AI generating schedules that I pasted into Notion, then manually re‑formatted and edited) created a lot of admin work, especially when plans changed.
- Manually updating dates and tasks when falling behind or getting ahead was tedious and discouraged frequent replanning.

**Approach**

- Created a lightweight interface showing what to work on today and how that aligns with each exam, with features that seamlessly allows the user to prioritise, shift dates, and see what's upcoming.
- YAML format intended to be easy for external tools (including AI) to read or write, allowing the use of AI-powered study schedule optimisation based off exam dates and user priorities.

**Impact**

- **Optimised study schedules:** Plans factor in deadlines and required coverage, rather than being a flat list of tasks.
- **Low‑friction replanning:** When reality changes, I update the data file and regenerate instead of manually editing dozens of entries.
- **Stronger AI leverage:** AI can work on a structured representation of the plan, not just produce text that I then have to clean up.

**Tech**

JavaScript, Python, HTML/CSS

---

## Contact

**GitHub:** [@BC-GB](https://github.com/BC-GB)  

Underlying repositories are private but available for review upon request.
