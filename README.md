# Case-study-on-Hishabee
A zero-dependency, dark-themed retail operations command center transforming raw transaction data into real-time interactive business intelligence.
# FIELD / LEDGER: Retail Operating Intelligence Control Room

A responsive, high-performance, single-page Business Intelligence (BI) command room and web dashboard. This application transforms raw operational datasets from `Bi_task_dataset_analysis_by_rocktim.xlsx` into an interactive executive command interface designed for manager sales tracking, shop follow-up analytics, and loan recovery auditing.

🖥️ **Live Web Application:** https://rocktimbarua.github.io/Case-study-on-Hishabee-/`

---

## 💡 Project Overview & Core Objectives
The dashboard consolidates operations and financial metrics covering the period of **April — June 2026**, with credit positions evaluated as of a **July 10, 2026** snapshot. It serves as a unified manager lens to isolate operational ownership across three primary business streams:

* **Sales Rhythm Acceleration:** Tracks month-over-month sales volumes, monitoring total book value velocity and manager performance momentum.
* **Follow-Up Intensity & Effectiveness:** Evaluates field teams by mapping user call frequency numbers directly against store subscription pay rates[cite: 1].
* **Loan Collections & Risk Control:** Audits repayment health across monthly cohorts, isolating descriptive performance lift (such as SMS reminders) alongside automated data anomaly flags[cite: 1].

---

## 🛠️ Built-In Features & Layout Capabilities

### 🎛️ 1. Global State Interactive Management
* **Dynamic Manager Lens:** A real-time dropdown filter (`#manager`) changes the scope across the entire interface seamlessly[cite: 1]. Selecting a manager instantly recalculates all portfolio KPIs, trends, tables, and charts to reflect only that employee's book of business without reloading the page[cite: 1].
* **Reactivity:** Built using highly responsive vanilla JavaScript state logic for fast data sorting, table searching, and UI view switching[cite: 1].

### 📊 2. Module Breakdown
* **Overview (Portfolio Pulse):** Renders high-level KPIs including 3-month sales totals (**BDT 167.9k** overall)[cite: 1], June sales step-ups (**+44.8%** growth rhythm)[cite: 1], shop conversion rates (**68%** overall)[cite: 1], total loan collections percentage (**67.2%**)[cite: 1], and outstanding exposures[cite: 1].
* **Sales Performance:** Compares monthly deal structures across all 12 field managers[cite: 1]. Built-in conditional formatting styles bar charts dynamically (lime for growth step-ups, rose for contractions)[cite: 1]. Includes an interactive, sortable scorecard table[cite: 1].
* **Follow-Up Scorecard:** Cross-references total store reach (150 shops, 543 calls)[cite: 1]. Automatically flags weak-signal managers falling below strict operational control thresholds (`calls per shop < 3.2` or `connect rate < 50%`)[cite: 1].
* **Loan Collections Register:** Groups repayment health by monthly cohorts (April vs. May vs. June)[cite: 1] and charts the descriptive lift of SMS outreach (showing an **85.8%** collection rate with SMS vs. **43%** without)[cite: 1]. Includes an advanced searchable data table filtered by text strings and loan statuses (`Fully Paid`, `Partly Paid`, `Not Paid`)[cite: 1].

### ⚠️ 3. Data Watch & Risk Engine Auditing
The dashboard contains a dedicated client-side validation logic that monitors data quality anomalies, keeping them visible to stakeholders[cite: 1]:
* **Overpaid Loans:** Identifies **6 credit accounts** where total paid values exceed total amounts due[cite: 1].
* **Future-Dated Repayments:** Identifies and flags **17 transaction logs** featuring payment dates recorded after the active July 10, 2026 ledger snapshot date[cite: 1].

---

## 📐 Architecture & Technology Stack

This system is built from scratch without bulky framework dependencies, ensuring high-speed rendering and zero setup friction[cite: 1].

* **UI Layer & Staggered Animations:** Engineered using clean, dark-themed styling with **Tailwind CSS**[cite: 1], structured geometric grid containers (`.grid2`, `.grid3`, `.kpis`)[cite: 1], glassmorphic panels[cite: 1], custom CSS keyframe animations[cite: 1], and standard system fallbacks (`<noscript>`)[cite: 1].
* **Charting Engine:** Custom charts built using canvas-driven rendering via **Chart.js (v4.4.4)**[cite: 1]. Custom options incorporate precise pixel radii settings, interactive hover boundaries, dynamic tooltips, and custom axis formatting rules[cite: 1].
* **Engine & Logic Layer:** 100% pure client-side **Vanilla JavaScript (ES6+)**[cite: 1]. Handles data array parsing, matrix math aggregations, multi-column alphanumeric table sorting, and structural string escaping routines (`esc()`) to prevent rendering script issues[cite: 1].

---

## 📁 Repository Structure

```text
├── index.html        # Unified single-page application (HTML5 structure, layout, styles, and logic)
└── README.md         # Technical architecture documentation and case study overview
