### **# Monitoring Logic Note – School Nutrition Programme**


\## Monitoring Philosophy

This project follows a \*\*programme monitoring and supportive supervision approach\*\*, not a performance evaluation approach.


The logic is based on the principle that:

> Effective programme management depends on timely information about coverage, reporting, and data quality.

---



\## Core Monitoring Questions

The monitoring system is designed to answer the following questions:


1\. Are meals being served as planned in schools?

2\. Are schools submitting their monthly reports on time?

3\. Are there data completeness or quality issues?

4\. Which schools require follow-up or supervisory attention?


No causal or outcome-related questions are addressed.
---



\## Validation Logic

Validation checks are implemented using Excel formulas to flag:

\- Meals served exceeding planned days

\- Invalid or zero enrolment values

\- Missing monthly reports

These checks \*\*flag issues without modifying raw data\*\*.

---


## Derived Indicators:

Derived indicators are calculated separately from raw data:


\### Meal Coverage (%)
Calculated as: Days Meals Served / Days Meals Planned

This reflects delivery consistency, not nutritional impact.

---

### Follow-up Required
A school is flagged for follow-up if:
- Meal coverage is below a defined threshold, OR
- Monthly report is not submitted, OR
- Data completeness is marked as “No”

This logic supports **action-oriented supervision**.

---

## Aggregation Logic
- School-level data is aggregated to block level using pivot tables
- District summaries provide a one-page snapshot
- No ranking or scoring of schools or blocks is performed

Aggregation is used only for visibility and planning.

---

## What This Monitoring System Does NOT Do
- Does not evaluate programme impact
- Does not rank schools or blocks
- Does not compare schools competitively
- Does not infer causes of low coverage

These exclusions are intentional and methodologically appropriate.

---

## Intended Use of Outputs
- Monthly district review meetings
- Block-level supervisory planning
- Follow-up visit prioritisation
- Reporting to state technical teams




