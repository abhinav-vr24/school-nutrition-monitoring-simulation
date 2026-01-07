\# District School Nutrition Programme Monitoring (Excel-Based)



\## Overview

This project demonstrates a district-level monitoring and reporting system for school nutrition programmes using an Excel-based workflow, designed to mirror real-world programme implementation and supervision practices in India.

The project focuses on routine monitoring, not impact evaluation. It shows how district and block teams can use school-level data to:

\- Track meal delivery coverage
\- Monitor reporting compliance
\- Identify data quality issues
\- Generate block and district summaries
\- Prepare follow-up action lists for supervision

The dataset used is simulated but programme-realistic, created solely to demonstrate monitoring logic, data management, and reporting workflows.

---



\## Why Excel?

District and block-level nutrition programme monitoring in India is predominantly conducted using Excel trackers, not advanced analytical tools.

This project intentionally uses Microsoft Excel to reflect:

\- Actual field practices
\- Skills expected from District Consultants and Data Support Personnel
\- Realistic constraints of programme implementation environments

The use of Excel here is a deliberate methodological choice, not a limitation.

---



\## Programme Context

School-based nutrition interventions play a critical role in improving child and adolescent nutrition outcomes. At the district level, effective implementation depends on:

\- Regular reporting from schools
\- Monitoring of meal delivery and coverage
\- Timely identification of gaps requiring follow-up
\- Coordination between education and health systems

District and block teams rely on routine school-level data to manage these programmes. This project simulates such a monitoring system.

---



\## Objective

The objective of this project is to:

> Design and demonstrate a district-level school nutrition programme monitoring system using Excel, focusing on coverage, reporting compliance, data validation, and follow-up readiness.

The project does not attempt to measure nutritional outcomes or programme impact.

---



\## Data Source

\- Simulated, programme-realistic school nutrition dataset
\- Designed to resemble routine monthly reporting formats used at district level
\- Covers one district, multiple blocks, and multiple schools for a single reporting month

\### Important Note

This dataset does not represent actual programme performance. It is used only to demonstrate monitoring and reporting workflows.

---



\## Unit of Observation
\- One row = One school × One reporting month

---

## Excel Workbook Structure
The core of this project is the Excel file:

### `school_nutrition_monitoring.xlsx`

It contains the following sheets:

### 1. Raw_Data
- Simulated school-level reporting data
- No formulas
- Mimics block-to-district data submission

**Key fields include:**
- District, Block, School ID & Name
- Enrolment
- Days school functioned
- Days meals planned and served
- IFA and deworming status
- Monthly report submission status
- Remarks

---

### 2. Validation_Checks
- Logical and data-quality checks using Excel formulas
- Flags issues such as:
  - Meals served exceeding planned days
  - Missing reports
  - Invalid enrolment values

This sheet demonstrates **data governance and validation practices**.

---

### 3. Derived_Indicators
- Monitoring indicators derived from raw data
- Examples:
  - Meal Coverage (%)
  - Follow-up Required flag

Raw data remains unchanged; indicators are calculated separately.

---

### 4. School_Level_Tracker
- Clean, operational monitoring view
- Used by district teams for routine review
- Highlights schools needing attention

---

### 5. Block_Summary
- Pivot-table based summary at block level
- Shows:
  - Number of schools
  - Average meal coverage
  - Reporting gaps
  - Follow-up load

Supports block-level review meetings.

---

### 6. District_Summary
- One-page snapshot for district leadership
- Used for:
  - Monthly review notes
  - Communication with state teams

---

### 7. Follow_Up_List
- Filtered list of schools requiring follow-up
- Supports:
  - Field visits
  - Supervisory calls
  - Corrective action planning

---

## Methodology (High-Level)
1. Design of programme-realistic dataset structure
2. Data entry in raw reporting format
3. Validation and logical checks using Excel formulas
4. Derivation of monitoring indicators
5. Preparation of operational and summary monitoring tables

No statistical inference or outcome evaluation is performed.

---

## Key Outputs
- School-level monitoring tracker
- Block-wise summary tables
- District-level monitoring snapshot
- Follow-up action list

All outputs are designed for **programme supervision and decision support**.

---

## Ethical & Data Use Statement
This project uses simulated programme data and does not include any individual-level or sensitive information. Outputs are descriptive and intended solely for demonstrating monitoring and reporting workflows.

---

## Skills Demonstrated
- Programme monitoring and supervision logic
- Excel-based data cleaning and validation
- Use of formulas, filters, and pivot tables
- District and block-level reporting
- Action-oriented follow-up planning

---

## Intended Audience
This project is intended to demonstrate skills relevant to:
- District Consultant – School Nutrition & Preconception Programmes
- Data Support Personnel (State/District level)
- Public health and nutrition programme monitoring roles

---

## Disclaimer
This project is for demonstration and learning purposes only and does not evaluate or represent actual programme performance.


