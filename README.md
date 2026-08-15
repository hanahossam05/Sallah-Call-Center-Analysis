# Call Center Performance Analysis (Power BI)

An end-to-end Power BI dashboard analyzing operational metrics, agent performance, and call volume trends for Salla call center projects across a 3-month period.

## Project Overview
This project transforms raw operational call logs into an interactive dashboard to monitor key performance indicators (KPIs), identify service bottlenecks, and compare monthly/daily efficiency trends.

## Tech Stack & Workflow
* **Tool:** Microsoft Power BI
* **Data Prep & ETL:** Power Query (consolidated 3 separate datasets, cleaned fields, standardized data types).
* **Data Modeling & DAX:** Built custom DAX measures for core KPIs and conditional formatting.
  * Measures include: `Total Calls`, `Handled Calls Rate`, `Abandoned Calls Rate`, and `Average Speed of Answer (ASA)`.
* **Visuals & UX:** Designed dynamic UI with simple navigation and side-panel filtering by Project and Date.

---

## Key Performance Insights

### 1. Overall Operations
* **Total Volume:** 1.74 Million calls managed by 16 agents.
* **Service Quality:** 98.68% overall handled rate with an average speed of answer (ASA) of 9 seconds.

### 2. Project-Level Breakdown
* **Project B:** Handled the largest volume (899,756 calls) but showed lower operational efficiency (ASA: 12 seconds, Abandoned Rate: 1.66%).
* **Project C:** Received the lowest volume (78,020 calls) but achieved top efficiency (ASA: 6 seconds, Handled Rate: 99.14%).

### 3. Forecasting vs. Reality
* **March:** Smallest forecasting gap (~102K variance), but recorded the weakest service quality (ASA: 14s, Abandoned Rate: 2.15%).
* **April:** Largest forecasting gap (~333K variance), yet achieved the best service quality (ASA: 7s, Abandoned Rate: 0.50%).
* **Takeaway:** Forecasting accuracy alone did not dictate operational performance.

### 4. Daily Patterns
* Volume peaks consistently on the **7th** (~80K calls) and **24th** (~75K calls) of each month.
* **31st of the month** had the lowest volume (27K calls) and the fastest response rate (ASA: 2s).

---
