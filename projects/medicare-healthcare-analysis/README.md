# Medicare Healthcare Performance Analysis

## Project Overview

This project analyses 1,000 healthcare patient records to assess hospital operational performance, patient experience and financial performance.

The analysis focuses on identifying areas where data can support improvements in patient satisfaction, waiting times, readmissions, departmental performance and financial sustainability.

## Business Questions

- Which departments generate the most revenue and profit?
- Which departments have the greatest operational challenges?
- How do waiting times relate to patient satisfaction?
- Which departments have the highest readmission rates?
- How does doctor-level patient satisfaction vary?
- Where should management prioritise operational improvements?

## Tools Used

- **Advanced Excel** — data cleaning, validation, PivotTables, PivotCharts, XLOOKUP, INDEX/MATCH, conditional formatting and data validation
- **Power BI** — interactive dashboard and KPI reporting
- **SQL** — filtering, aggregation, sorting and joining data
- **Python** — exploratory data analysis, correlation analysis and visualisation

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Patient records | 1,000 |
| Total revenue | £23,956,217 |
| Average treatment cost | £5,690.41 |
| Average waiting time | 78 minutes |
| Average readmission rate | 13.29% |
| Average patient satisfaction | 79 |

## Key Findings

### 1. Emergency is the main operational concern

Emergency recorded the longest average waiting time at **109 minutes**, the lowest patient satisfaction score at **72**, and the highest readmission rate at **18.4%**.

This combination makes Emergency the highest-priority area for operational investigation.

### 2. General Surgery and Cardiology are major financial contributors

General Surgery generated approximately **£5.07M in revenue and £3.86M in profit**, while Cardiology generated approximately **£4.13M in revenue and £3.18M in profit**.

However, both departments also recorded relatively high readmission rates, indicating that financial performance should be considered alongside quality and patient-outcome measures.

### 3. Radiology and Pediatrics show strong operational performance

Although Radiology and Pediatrics generated less revenue than the highest-performing departments, they recorded shorter waiting times, higher patient satisfaction and lower readmission rates.

Their operational practices may provide useful benchmarks for other departments.

### 4. Doctor-level satisfaction varies

Dr. Byrd and Dr. Reyes recorded the highest patient satisfaction scores, while Dr. Brooks and Dr. Clark recorded the lowest among the doctors reviewed.

These differences should be interpreted carefully because satisfaction may also reflect department, caseload and patient characteristics rather than individual performance alone.

## Recommendations

1. **Prioritise Emergency Department improvement** through review of triage, staffing, capacity and patient-flow processes.
2. **Benchmark successful workflows** from departments with shorter waiting times and stronger patient experience measures.
3. **Investigate readmissions** in Emergency, General Surgery and Cardiology to identify potentially preventable cases.
4. **Use doctor-level metrics carefully**, considering department and workload differences before drawing conclusions about individual performance.
5. **Balance financial performance with quality outcomes** by monitoring revenue alongside satisfaction, waiting times and readmissions.

## Limitations

- Patient satisfaction is self-reported and may be affected by factors outside departmental control.
- Staffing information was insufficient to determine whether Emergency waiting times were primarily driven by patient volume or staffing constraints.
- Observed relationships should not automatically be interpreted as causal relationships.

## Project Files

- `Excel/` — source analysis and workbook
- `Power-BI/` — Power BI dashboard
- `SQL/` — SQL analysis scripts, where applicable
- `Python/` — Python analysis scripts, where applicable

## Outcome

The project demonstrates an end-to-end approach to healthcare data analysis: preparing data, analysing performance, creating visualisations, identifying operational issues and translating findings into practical recommendations.
